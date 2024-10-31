# SpatialTemporalProject
**Data Science Spatial-Temporal Analysis Project**

This project conducts a spatial-temporal analysis of personal movement data, using location history exported from Google's **Timeline** feature on an Android device. The project explores weekly movement patterns, particularly within a college setting, by generating visualizations to understand typical routes and identify anomalies.

### How I Obtained the Dataset

The dataset was obtained directly from the **Timeline** feature on my Android device. Google previously allowed data exports via device settings, offering a simpler alternative to the Google Takeout website. Here’s how I accessed and exported the data:

1. **Navigate to Location Services**:
   - Opened **Settings** on the Android device.
   - Selected **Location** > **Location Services**.

2. **Access Timeline**:
   - Under Location Services, selected **Timeline**.

3. **Export Data**:
   - Tapped on **"Export Timeline data"** to generate a JSON file containing my location history. This data includes **timestamps** and **GPS coordinates** for each recorded location point, providing a foundation for the spatial-temporal analysis.

### Project Goals and Visualizations

This project aims to uncover movement patterns during a college semester, focusing on weekday routes and potential deviations from usual paths. The primary visualizations are heatmaps that highlight:

- **Class Days (MWF vs. TT)**: Movement patterns are differentiated by typical class schedules, providing insights into regular routes and campus-specific locations.
