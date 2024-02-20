---
sidebar_position: 1
# slug below makes this page the landing page
slug: /
---

# Gafargan Intro

Below is a short summary of Gafargan project. It descriibes goals and objectives, technology stack, and how to get started depending on your goals.

## Goals and Objectives

Gafargan [_pronounced as_ `/ˈɡɑfɑrɡɑn/`, _means dictionary in Lezgi_] is an online dictionary that aims to help people of endangered languages to preserve and enrich their languages. The goal is that through Gafargan, native people and linguists can easily access and contribute to their languages' dictionaries. The project is open source and we welcome contributions from anyone who is interested in preserving and enriching endangered languages.

Currently, Gafargan has most of its data available for [Lezgi language](https://en.wikipedia.org/wiki/Lezgian_language), but there is also dictionary data for [Tabasaran](https://en.wikipedia.org/wiki/Tabasaran_language) and we are hoping to add more languages in the future.

## Technology Stack

Our web application is built using the following stack:

**Frontend** [Github link](https://github.com/LekiTech/gafargan-web): 

- Next.js
- React
- TypeScript

**Backend** [Github link](https://github.com/LekiTech/gafalag-api):
- Java
- Spring Boot
- PostgreSQL

**DevOps**

- Docker
- [Docker Hub](https://hub.docker.com/r/lekitech/gafalag-api)
- GitHub Actions

## Getting Started

### I want to contribute to the project

If you want to contribute to the project, you can start by reading the [contributing guide](./category/contributing-guide). This guide will help you understand how to contribute to the project.

These are the main areas you can contribute to:

- **Frontend**: You can contribute to the frontend by adding new features, fixing bugs, or improving the user interface. You can find the frontend source code [here](https://github.com/LekiTech/gafargan-web)
- **Backend**: You can contribute to the backend by adding new features, fixing bugs, or improving the API. You can find the backend source code [here](https://github.com/LekiTech/gafalag-api)
- **Data parsing**: You can contribute to the data by parsing existing dictionaries to the Gafargan data structure. You can find the data parsing source code that we have used most [here](https://github.com/LekiTech/html-parser), but of course you can use any other method to parse the data as long as it follows the [data structure guide](./category/data-structure-guide)
- **Documentation**: You can contribute to the documentation by adding new pages, fixing typos, or improving the existing documentation or by adding more comments to the source code
- **Telegram bot**: You can contribute to the Telegram bot by adding new features, fixing bugs, or improving the bot. You can find the source code of the bot [here](https://github.com/MagomedovArthur/gafarganbot)
- **Mobile app**: You can contribute to the mobile app by adding new features, fixing bugs, or improving the app. You can find the source code of the app [here](https://github.com/LekiTech/GafarganMobile)

### I want to use the dictionary data

If you want to use the dictionary data, you can access the data through the API, database backups or `JSON` files. Because of complex nature of the data, we recommend you first read the [data structure guide](./category/data-structure-guide) to understand how to use the data.

### I want to run my own backend instance of Gafargan

If you want to run your own instance of Gafargan, the best you can do is using the Docker image. You can find the Docker image of the API [here](https://hub.docker.com/r/lekitech/gafalag-api). You can also find the source code of the backend [here](https://github.com/LekiTech/gafalag-api)