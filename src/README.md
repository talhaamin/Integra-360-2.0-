# INTEGRA 360 Frontend Apps

This directory contains the ASP.NET Core 8 Razor Pages applications that power the INTEGRA 360 (2.0) user experience. These apps are API-first clients for `Dhms.WebAPI` and are organized as app-specific portals sharing a common architectural pattern.

## App Portfolio

- `Dhms.Main` - ecosystem launchpad
- `Dhms.Admin` - platform admin and SaaS operations
- `Dhms.Web` - core HMIS
- `Dhms.PATIENT` - patient portal
- `Dhms.PROVIDER` - provider workspace
- `Dhms.SCMweb` - supply chain management
- `Dhms.Finance` - finance
- `Dhms.HR` - human resources
- `Dhms.CRM` - customer relationship management
- `Dhms.TASK` - task and work management
- `Dhms.POS` - point of sale
- `Dhms.IMS` - institution management system
- `Dhms.DCLMS` - dairy and livestock operations

## Frontend Architecture

- Razor Pages UI
- API-first communication model
- `PageModel -> Service -> IApiClientService -> Dhms.WebAPI`
- AdminLTE + Bootstrap 5 + jQuery + DataTables + Chart.js
- FluentValidation
- AutoMapper
- HttpClientFactory + Polly retry policies
- SignalR client integration
- Serilog request, file, and console logging
- Policy-based authorization
- JWT + refresh token in secure HttpOnly cookies
- Tenant and site context propagation via `X-Tenant-Id` and `X-Site-Id`
- Security middleware including CSP, anti-forgery, maintenance mode, and exception handling
- Health checks exposed through `/health`

## Shared Platform Behaviors

Across the app suite, the frontend is designed to support:

- Role-based navigation and permission-aware UI
- Tenant feature flag evaluation
- Module access checks per user
- Shared layout, cards, tabs, dashboards, and administration workflows
- Real-time notifications and operational refresh patterns

## Configuration

Each app typically includes:

- `appsettings.json`
- `appsettings.Development.json`

Common configuration sections include:

- `ApiSettings`
- `JwtSettings`
- `TenantSettings`
- `SignalRSettings`
- `FeatureToggles`
- `ModuleAccess`

## Run Locally

```powershell
dotnet restore
dotnet run --project src/Dhms.Admin/Dhms.Admin.csproj
dotnet run --project src/Dhms.Web/Dhms.Web.csproj
```

Run any other portal by targeting its corresponding project file under `src/`.

## Docker

Each app includes its own Dockerfile. Example:

```powershell
docker build -f src/Dhms.Admin/Dockerfile -t dhms-admin .
docker build -f src/Dhms.Web/Dockerfile -t dhms-web .
```

## Notes

- `Dhms.WebAPI` must expose the expected endpoints for authentication, tenants, module access, permissions, and functional modules.
- Several portals share common design language and security behaviors while presenting app-specific workflows.
- XML documentation warnings may appear because projects generate XML docs by design.

For the product overview, module descriptions, SaaS 2.0 capabilities, and promotional content, see the repository [README.md](../README.md).
