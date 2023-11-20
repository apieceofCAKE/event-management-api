# Event Management API

## Overview

Advanced web development class assessment. It's an API specification, done according to requirements and trying to follow RESTful principles.

The endpoints are tagged according to the actors that have access to them, which means tha the same endpoint can be available to more than one actor, with some method restrictions. For example, some GET requests be made by both users and admins, but POST and DELETE are reserved for admins.

## Getting Started

We recommend using [SwaggerHub](https://swagger.io/tools/swaggerhub), with its editor and mock server for testing.

## Authentication

This API uses HTTP basic authentication for most of its endpoints. Ensure to include valid credentials in your requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
