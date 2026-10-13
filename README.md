# How to Customize the Blazor TreeMap Component

## Overview

This sample demonstrates how to customize the Syncfusion [Blazor TreeMap](https://www.syncfusion.com/blazor-components/blazor-treemap) component to visualize hierarchical employee data. The application configures custom rendering direction, formatted labels, hierarchical grouping levels, and styled group headers to improve data presentation. It showcases how TreeMap levels can be used to organize and display grouped information while maintaining a clear visual hierarchy.

## Key Features

- Uses the `SfTreeMap` component to visualize employee data based on `EmployeeCount`.
- Configures custom item rendering with `RenderDirection="TopRightBottomLeft"`.
- Displays formatted labels using `LabelPath` and `LabelFormat`.
- Supports word-wrapped labels with `InterSectAction="WrapByWord"`.
- Customizes leaf item appearance using borders, colors, spacing, and label styles.
- Groups data hierarchically by `Country`, `JobDescription`, and `EmployeeCount` using `TreeMapLevel`.
- Customizes group headers with `HeaderFormat`, `HeaderAlignment`, and `HeaderHeight`.
- Binds data from a strongly typed `List<Employee>` collection.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone this repository.
2. Open the repository folder in Visual Studio 2022.
3. Restore NuGet packages.
4. Set the Blazor WebAssembly project as the startup project if required.
5. Build the project.
6. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Clone this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

5. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/Index.razor` — Main sample page containing TreeMap configuration, level definitions, data model, and sample employee data.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://help.syncfusion.com/chart-sdk/blazor/treemap/getting-started-webapp).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.