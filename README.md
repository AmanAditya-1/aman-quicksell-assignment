# Kanban Board App

## Overview

This project is a Kanban board application built with ReactJS, allowing users to manage and organize tickets fetched from the [Quicksell API](https://api.quicksell.co/v1/internal/frontend-assignment). Users can group and sort tickets based on various criteria, making it a powerful tool for project management.

## Features

- **Ticket Data Management**

  - Fetches and displays tickets from the Quicksell API.
  - Presents the tickets on a Kanban-style board.

- **Custom Grouping**

  - Group tickets by Status, User, or Priority.

- **Sorting Options**

  - Sort tickets by Priority or Title.

- **Priority Levels**

  - Tickets are categorized into priority levels, ranging from Urgent (4) to No Priority (0).

- **Responsive Design**

  - Visually appealing and fully responsive design.
  - Styled using pure CSS for consistent layout across devices.

- **Icon Integration**

  - Icons are implemented using `react-icons` for various elements in the application.

- **State Persistence**
  - Saves user's view preferences (grouping and sorting) in local storage, preserving the state even after page reloads.
