# Getting Started with the Blazor Bullet Chart

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Bullet Chart](https://www.syncfusion.com/blazor-components/blazor-bullet-chart) component in a Blazor WebAssembly application. The application shows how to visualize actual values against target values using a compact bullet chart representation. It demonstrates data binding, chart customization, target indicators, titles, subtitles, dimensions, and interactive tooltip support. This sample serves as a practical starting point for developers who want to integrate performance tracking and KPI visualization into Blazor applications.

## Key Features

- Renders a Syncfusion Bullet Chart using the `SfBulletChart` component.
- Binds chart data through the `DataSource` property using a local `List<ChartData>` collection.
- Maps actual and target values using the `ValueField="FieldValue"` and `TargetField="TargetValue"` properties.
- Configures the quantitative scale with `Minimum`, `Maximum`, and `Interval` properties.
- Displays chart header information using the `Title` and `Subtitle` properties.
- Enables interactive tooltip support through the `BulletChartTooltip` component with `Enable="true"`.
- Defines qualitative performance ranges using the `BulletChartRangeCollection`.
- Customizes range appearance with multiple `BulletChartRange` elements and color settings.
- Demonstrates performance comparison between an actual value (`FieldValue`) and a target value (`TargetValue`).
- Uses a strongly typed `ChartData` model to represent Bullet Chart data.
- Configures custom chart dimensions using a container element with fixed width and height.
- Provides a minimal Blazor WebAssembly example for learning Bullet Chart configuration and data visualization.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `GettingStarted.sln`.
3. Restore all NuGet packages.
4. Build the solution.
5. Ensure the hosted Blazor application starts successfully.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open an integrated terminal.
3. Navigate to the repository root directory.
4. Restore project dependencies:

```bash
dotnet restore
```

5. Run the application:

```bash
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.

## Project Structure

`Client/Pages/Index.razor` - Main sample page that renders the `SfBulletChart`, configures titles, value and target mappings, qualitative ranges, tooltip support, and local chart data.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Documentation: https://help.syncfusion.com/chart-sdk/blazor/bullet-chart/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.