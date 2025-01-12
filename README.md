# Scrumtrulescent Magazine

Welcome to **Scrumtrulescent Magazine**, an entertainment blog where creativity meets insightful commentary on pop culture, movies, music, and more! This blog is powered by Payload CMS's website template, making content management seamless and development flexible.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User-Friendly CMS**: Built with Payload CMS for easy content creation and management.
- **Responsive Design**: Mobile-first layout for optimal viewing on any device.
- **SEO-Optimized**: Structured to maximize search engine visibility.
- **Rich Media Support**: Effortlessly add images, videos, and other media to enhance content.
- **Customizable**: Easily extend and modify features to meet your needs.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js with Payload CMS
- **Database**: MongoDB
- **Styling**: SCSS and CSS Modules
- **Deployment**: Vercel (or any Node.js-compatible hosting platform)

## Getting Started

To get started with Scrumtrulescent Magazine, follow the steps below.

### Prerequisites

Ensure you have the following installed on your system:

- Node.js (>= 16.x)
- npm or Yarn
- MongoDB (local or cloud instance)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/scrumtrulescent-magazine.git
   cd scrumtrulescent-magazine
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up the database**:
   Ensure your MongoDB instance is running. Create a database for the project and note the connection string.

4. **Create environment variables**:
   Create a `.env` file in the root directory and add the following:
   ```env
   PAYLOAD_SECRET=your-secret-key
   MONGODB_URI=mongodb+srv://your-database-uri
   PORT=3000
   ```

### Run the Project Locally

Start the development server:
```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser to view the blog.

## Configuration

### Payload CMS Admin Panel

The admin panel is accessible at `/admin`. Use this panel to create and manage blog posts, categories, authors, and media.

### Customizing the Design

All styling is located in the `src/styles` directory. Modify the SCSS files to change the blog's appearance.

### Adding Custom Features

Extend functionality by adding custom collections, hooks, or plugins in the Payload CMS configuration file (`payload.config.ts`). Refer to the [Payload CMS documentation](https://payloadcms.com/docs) for guidance.

## Deployment

Scrumtrulescent Magazine is optimized for deployment on Vercel. To deploy:

1. **Create a new Vercel project**:
   Link your GitHub repository to Vercel.

2. **Set environment variables**:
   In the Vercel dashboard, add the same environment variables from your `.env` file.

3. **Deploy**:
   Trigger a deployment from the Vercel dashboard or push changes to the main branch.

Visit your deployed blog at the provided URL.

## Contributing

We welcome contributions to Scrumtrulescent Magazine! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Open a pull request detailing your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Enjoy building and growing your entertainment blog with Scrumtrulescent Magazine!

