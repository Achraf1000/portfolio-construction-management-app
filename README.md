# Construction Management App

Public portfolio presentation of a mobile platform designed to coordinate construction-site operations, field teams and daily workflows.

> This repository contains presentation material and static screenshots approved for public portfolio use. The original application was developed in a professional context and remains in a separate private repository. No source code, credentials or confidential documents are included here.

## Project overview

The application brings several field processes into one mobile experience: secure access, team attendance, measurement collection, estimation, operational issue tracking and management dashboards.

## Business goals

- Give field teams a single mobile entry point for daily operations.
- Reduce fragmented communication between site and management teams.
- Standardize attendance, measurement and issue workflows.
- Provide role-based visibility and operational indicators.
- Support multilingual users in a field-friendly interface.

## Main capabilities

- secure authentication and session storage;
- role- and permission-based access;
- employee check-in and check-out;
- team assignment, delegation and validation;
- field measurements and estimation tracking;
- issue reporting and resolution monitoring;
- quality-control and delivery-reception workflows;
- dashboards and performance indicators;
- French and Arabic localization.

## Technology overview

| Area | Technologies |
| --- | --- |
| Mobile application | Flutter, Dart, Material Design |
| API communication | Dio, REST APIs |
| Mobile security | Secure storage, token-based authentication |
| Backend | Python, FastAPI, Pydantic |
| Data access | SQLAlchemy, relational database |
| Organization | Modular services, shared security and data layers |

## Architecture

See [docs/architecture.md](docs/architecture.md) for the sanitized technical overview.

## Screenshots

### Multilingual authentication

| French | Arabic |
| --- | --- |
| ![French login](docs/screenshots/login-fr.jpeg) | ![Arabic login](docs/screenshots/login-ar.jpeg) |

### Team operations

| Team dashboard | Team setup | Task delegation |
| --- | --- | --- |
| ![Team dashboard](docs/screenshots/team-dashboard.jpeg) | ![Team setup](docs/screenshots/team-setup.jpeg) | ![Task delegation](docs/screenshots/task-delegation.jpeg) |

### Field workflows

| Site selection | Face attendance | Truck reception |
| --- | --- | --- |
| ![Site selection](docs/screenshots/site-list.jpeg) | ![Face attendance](docs/screenshots/face-attendance.jpeg) | ![Truck reception](docs/screenshots/truck-reception.jpeg) |

Additional views covering performance, attendance history, onboarding and personnel management are available in [`docs/screenshots`](docs/screenshots/).

## My contribution

- structured a modular mobile application around operational domains;
- integrated secure authentication and permission controls;
- connected Flutter interfaces to multiple backend services;
- designed field-oriented workflows and dashboards;
- implemented localization and reusable application modules.

## Skills demonstrated

`Flutter` · `Dart` · `FastAPI` · `REST API` · `JWT` · `RBAC` · `SQLAlchemy` · `Mobile UX` · `Internationalization`

## Confidentiality

The implementation, infrastructure configuration and confidential business data are intentionally excluded. The published images are static interface captures approved for portfolio use; this repository is not a distributable version of the original product.

## License

The documentation and anonymized visual material are shared for portfolio review under the terms in [LICENSE](LICENSE).
