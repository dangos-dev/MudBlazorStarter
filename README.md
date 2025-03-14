# Blazor Starter Template with MudBlazor

This template is designed to help you build modern, responsive web applications using Blazor and MudBlazor, combining the power of C# and Razor with a beautiful and customizable UI framework.

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/template/tLwnkc?referralCode=Al2B-n)

## Features

- **Blazor Framework**: Build interactive and dynamic single-page applications using C# and Razor.
- **MudBlazor UI Components**: Leverage a rich library of powerful, modern, and easy-to-use components.
- **Responsive Design**: Build UIs that adapt seamlessly to different screen sizes.
- **Ready to Customize**: Quickly configure and extend the template for your own projects.

## File Structure

### Key Files:
- **`App.razor`**:
  The main application layout component.

- **`MainLayout.razor`**:
  Provides the main page layout. Easily customizable for navigation bars, headers, and footers.

- **`Index.razor`**:
  The default landing page for the project, showcasing the template's features.

- **MudBlazor Integration**:
    - `MudTable`, `MudContainer`, `MudText`, and many other components are pre-integrated into the project.

## Setup Instructions

### Prerequisites
Before starting, ensure you have the following installed:
- [.NET 9 SDK](https://dotnet.microsoft.com/download)
- A Blazor-compatible code editor, e.g., [JetBrains Rider](https://www.jetbrains.com/rider/) or Visual Studio.

### Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/dangos-dev/MudBlazorStarter.git
   cd MudBlazorStarter
   ```

2. Restore dependencies:
   ```bash
   dotnet restore
   ```

3. Run the application:
   ```bash
   dotnet run
   ```

4. Open your browser and navigate to `https://localhost:1208` to see the application in action.

## MudBlazor Overview

[MudBlazor](https://mudblazor.com/) is a modern, open-source Blazor UI library that focuses on clean design and easy-to-use components. This template integrates MudBlazor, allowing you to:
- Quickly build responsive web interfaces.
- Apply customizable themes and styles.
- Use components like tables, charts, dialogs, and forms out of the box.

### Useful Links:
- [Learn More about Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
- [Learn More about MudBlazor](https://mudblazor.com/)

## Customization

### Modify the Theme:
You can easily update the theme by customizing the `MudTheme` in your `MainLayout.razor` or configuring it globally.

### Add New Pages:
1. Create a new `.razor` file in the `Pages` folder.
2. Add the route using the `@page` directive.
3. Add new MudBlazor components to the page as needed.

---

Build amazing web apps with **Blazor** and **MudBlazor** today! 🎉