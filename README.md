# Data-anaysis
Examine the correlation between internet speed and urban infrastructure using Tokyo (smart city) and Tottori (developing city) as case studies.

Tools Used in the Project:

    Programming Languages & Libraries:
        Python (for data analysis and modeling)
        Pandas & NumPy (data manipulation and numerical computations)
        GeoPandas (spatial data analysis and processing)
        Matplotlib & Seaborn (data visualization including heatmaps, scatter plots, and time-series analysis)
        Scikit-learn (KDTree for spatial analysis, linear regression modeling)

    Data Sources:
        Ookla Speedtest Dataset: Provides quarterly internet performance metrics (download/upload speeds, latency, test counts) for 2020.
        VIIRS Annual Composites: Satellite-based dataset containing global light intensity data as an urban activity indicator.

    Data Processing & Analysis:
        Spatial Integration: Geometries were used to align internet performance data with urban light intensity metrics.
        Missing Data Handling: KDTree-based nearest neighbor approach to assign missing internet speed data.
        Statistical Tests:
            Pearson & Spearman Correlation (to measure relationships between variables)
            Z-test & Chi-square Test (to compare city-wise internet speeds and digital connectivity)
        Machine Learning Model:
            Linear Regression Model (to predict internet speed based on urban radiance and other factors).
