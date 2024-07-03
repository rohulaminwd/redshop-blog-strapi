# RedShop Blog Strapi

A Strapi application for managing the RedShop Blog.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Description

RedShop Blog Strapi is a content management system built with Strapi. It includes various plugins for internationalization, user permissions, and cloud storage using Cloudinary.

## Features

- **Internationalization (i18n)**: Manage content in multiple languages.
- **User Permissions**: Manage user roles and permissions.
- **Cloud Storage**: Use Cloudinary for media storage.
- **React Integration**: Frontend built with React.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Node.js (version >=18.0.0 <=20.x.x).
- You have installed npm (version >=6.0.0).
- You have a PostgreSQL database setup.
- You have a Cloudinary account for media storage.

## Installation

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/redshop-blog-strapi.git
cd redshop-blog-strapi

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```

npm run develop

# or

yarn develop

```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```

npm run start

# or

yarn start

```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```

npm run build

# or

yarn build
