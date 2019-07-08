# WormProfiler
For analysis of profiles by large-particle flow cytometry
Welcome to WormProfiler v1.2

NOTICE
WormProfiler requires the MATLAB Runtime to function. You may install this runtime for free at:

https://www.mathworks.com/products/compiler/matlab-runtime.html

Select the R2018b (9.5) version


Using WormProfiler
1. WormProfiler imports profile data (using the standard format from FlowPilot export) and normalizes all worm
   lengths to 100. 
2. When exporting analyzed profiles, there are two options: "Average" or "All"
   a. "Average" outputs a single profile in .txt format which comprises the average of all worm profiles imported
   b. "All" exports every imported profile as length-normalized profiles in .txt format.
3. Note that WormProfiler will plot the Average profile regardless of the selection for output. This feature may
   change in the future.

