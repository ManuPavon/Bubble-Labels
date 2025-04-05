# Bubble-Labels

Here is a resource about how to create some nice labels in a different shape, a bubble.

## Bubble Column Chart Design for Power BI

This repository contains resources for implementing a bubble-style column chart design in Power BI. This custom design transforms the standard square or rounded square column labels into bubble-shaped labels, creating a more visually engaging chart experience.

## Repository Contents

- **Bubble Labels.pbix**: A sample Power BI file demonstrating the bubble column chart implementation
- **Theme - Bubble.json**: Theme JSON file with the necessary configurations for resizing the bubble effect
- **Visual Bubble Label.png**: Visual preview of the bubble column chart design

## JSON Configuration (add to the last part of your pbi theme)

```json
{
  "visualStyles": {
    "lineClusteredColumnComboChart": {
      "*": {
        "lineStyles": [
          {
            "showMarker": true,
            "markerShape": "circle",
            "markerSize": 35
          }
        ]
      }
    }
  }
}
```

## How It Works

This design modification replaces traditional column chart bars with circular bubble markers. The key advantage is improved visual aesthetics while maintaining data clarity. You can adjust the size of the bubble markers to suit your specific visualization needs.

## Implementation Instructions

1. Download the JSON theme file from this repository
2. In Power BI Desktop, go to View → Themes → Browse for themes
3. Select the downloaded JSON file
4. Apply the theme to your report
5. Important: Adjust the marker sizing in your column chart properties to achieve the optimal bubble appearance

## Customization Options

You can customize the bubble design by modifying the following parameters in the JSON file:
- Bubble size (marker radius)
- Color palette
- Border thickness
- Transparency levels

## Preview

The included preview image shows how the bubble design transforms standard column charts into a more modern visualization.
![imagen](https://github.com/user-attachments/assets/e5adf078-4e30-4b6e-b745-7c29c72e2753)
