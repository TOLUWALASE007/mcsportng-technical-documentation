# McSportng Documentation

This repository contains the technical documentation website for the McSportng sports management platform. It serves as a comprehensive guide for QA engineers, developers, and stakeholders, detailing the features and user roles across different sports portals.

## Features

- **Responsive Design**: Fully responsive layout optimized for mobile and desktop devices.
- **Sticky Navigation**: Headers remain accessible while scrolling for easy navigation.
- **Mobile Menu**: Includes a hamburger menu with an overlay for mobile users.
- **Role-Based Documentation**: Detailed guides for distinct user roles (Admin, Coach, Player, etc.) tailored to each sport.

## Technologies Used

- **HTML5**: Semantic structure for documentation pages.
- **Tailwind CSS**: Utility-first CSS framework for styling (via CDN).
- **Vanilla JavaScript**: Lightweight scripts for interactive elements like mobile navigation.

## Project Structure

The project is organized into a root directory containing general documentation and specific portals for different sports.

### Root Directory

- `index.html`: Main landing page and platform overview.
- `admin.html`: Documentation for Super Admin controls and system management.
- `auth.html`: User authentication, registration, and onboarding workflows.
- `public.html`: Details on public-facing pages and accessible content.
- `sports.html`: Overview of sport-specific modules and features.
- `scout.html`: Documentation for Scout portal and features.

### Sport Portals

Each sport has a dedicated portal with documentation tailored to its unique requirements.

#### Baseball Portal (`/baseball_portal`)
- `index.html`: Overview of the Baseball portal.
- `coach.html`: Features and tools for baseball coaches.
- `player.html`: Dashboard and profile management for baseball players.
- `org.html`: Organization-level management for baseball leagues.
- `team.html`: Team administration and roster management.

#### Football Portal (`/football_portal`)
- `index.html`: Overview of the Football portal.
- `agent.html`: Features for sports agents managing players.
- `coach.html`: Tools for football coaches, including strategy and training.
- `player.html`: Player profile, stats, and career management.
- `org.html`: Administrative tools for football organizations.
- `team.html`: Team management and squad coordination.

#### Golf Portal (`/golf_portal`)
- `index.html`: Overview of the Golf portal.
- `coach.html`: Coaching tools for golf instructors.
- `player.html`: Golfer profile, handicap tracking, and tournament history.
- `org.html`: Management features for golf clubs and organizations.

## How to Run locally

Since this project relies on static HTML files and a CDN for styling, no build process or package installation is required.

1.  Clone or download the repository.
2.  Navigate to the project directory.
3.  Open `index.html` (in the root or any portal folder) in a modern web browser to view the documentation.

## Customization

The interface is styled using Tailwind CSS utility classes. To modify the design, simply edit the class attributes directly within the HTML files. Navigation logic is embedded in script tags within each file.
