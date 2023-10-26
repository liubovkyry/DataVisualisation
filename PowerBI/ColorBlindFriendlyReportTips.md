# The best charts for color blind viewers

Source: https://www.datylon.com/blog/data-visualization-for-colorblind-readers#:~:text=The%20first%20rule%20of%20making,out%20of%20these%20two%20hues.



   How do we see the world in colors? It all starts with the light. The light can come from the Sun, fire or a lamp sending waves of different lengths. The surfaces around us have different capacities for absorbing wavelengths, so some of the waves are absorbed, while others are reflected. The ones that are reflected can be perceived by our eyes. These waves go through the cornea and pupil and hit the retina. The retina consists of cones and rods. Cones are the ones that are responsible for color perception. The combination of waves that hit the cones form in our brain the perception of color.
   ![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/080ff03d-4873-4ba0-8d3e-53ee53e49248)

   There are three types of cones: The first type is sensitive to long wavelengths (starting from red, peaking at yellow, and declining at green). The second type is sensitive to middle wavelengths (starting at orange, peaking at green, and declining at blue). The third type is sensitive to short wavelengths (starting at green and peaking at blue).
   
### Table of contents
 

1. What colors can color blind people see?

2. Color blind palette

3. How to make charts color blind friendly?

4. Good and bad charts for color blind viewers

Comparison charts
Correlation charts
Part-to-whole & hierarchical charts
Data over time charts
Distribution



   ## What colors can color blind people see?
Actually, it depends on what type of cones don't work. There are three common types: protanopia (red-blind), deuteranopia (green-blind), and tritanopia (blue-blind). There can also be an intermediate state, color weakness - when the colors can be distinguished but some of the hue details are lost. There’s also a very rare state when all the cones are not working and the person is completely color blind – it’s called complete achromatopsia. In the next picture, the simulation of what colors can color blind people see is presented.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/c778dea6-67c4-4a9a-98ef-632123da3f30)

## Color blind palette
The picture below shows that for all of the types of color blindness there is a pair of colors that can be distinguished – red and blue – these are color blind safe colors. As for the green, it is the number one among the colors to avoid for the color blind. Most of the issues for colorblind people come from the prevalence of red-and-green combinations as a pair of opposites in design. The first rule of making a palette for colorblind – avoid combining red and green. So if you’re aiming to create a color blind-friendly palette try to use only two basic hues: blue and red (orange and yellow will also fit). The other colors should be made out of these two hues. All the variations can be made by using different saturation or lightness of the basic color. Based on these rules we’ve created a color blind palette and checked it for three color blindness types. 

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/c2c6fcdc-d547-4c83-86eb-ac5020847e03)

As you can see the palette worked for all types of color blindness, but you should always be aware that the variation of color-blind colors can vary significantly from person to person, so it’s always important to double-check. If you have a friend who is colorblind – ask for feedback. Alternatively, you can look up a colorblind community online and reach out to them. Don’t forget about people with complete color blindness and remember that 100% best colors for colorblind are black and white. So if your visualization works in greyscale you should be safe. Another advantage of using black and white data visualization is that they’re print-ready. But remember, if the palette is grayscale one should use other tools to distinguish chart elements.

There are a few tools that can help you to check your visuals. For this article, a color-blind simulator was used from the Colorblindor website.

https://www.color-blindness.com/2016/10/27/new-release-of-color-blindness-simulator/

There’s also a helpful internal tool in Adobe Illustrator. You can access it under View > Proof Setup > Color-Blindness - Protanopia-type or Deuteranopia-type.

## How to make charts color blind friendly?
Use shapes and icons as an addition or alternative to color-coding. In case one needs to use colors that are not perceptible by colorblind users, a chart can be saved by using icons as an addition to color, duplicating its informational function.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/d767d385-e68d-46e3-b9ca-35dd9dbccc9b)

Typically, it’s better to use direct labels instead of a legend – it saves the time and attention of a reader. Another advantage of direct labels is its ability to fix the usage of palettes that are not color blind friendly.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/670a03b5-5d47-4c3c-b3fc-1003e0db99c1)



For line charts and their variations, dashed lines and lines with various stroke thicknesses can be a very helpful alternative to coloring.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/bac11814-f899-4ce3-b529-e4d622858d5e)

Adding strokes around chart elements might also help to distinguish one element from the other if the color might look the same for color-blind users.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/17ed931f-d7b4-4e2c-8ac4-7d57d8173817)

If the usage of color is inevitable try to use a single hue palette. It will make the chart readable for all kinds of color blindness including monochromacy (when no color can be recognized). The second option is to use a red-yellow-blue palette. It will work for all kinds of color blindness except monochromacy.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/62729719-6414-45fb-a1df-c189498101ee)

Use color for groups, not the individual categories. By doing that the number of colors will be reduced, as well as visual clutter and the possibility of color confusion.

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/f276deb3-01ea-4442-8d28-7ada91a49566)

### Comparison charts
 

#### ✅ Good choice: Dot plot (and Parallel coordinates)
![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/3809b335-ae8a-4f8a-8626-e33d8eaf7e40)

Dot plot could be both great and challenging. If the color is used for dot differentiation – it won’t work well. But if the dots are substituted with different colors per category it will make a very good choice for comparison of multiple categories at the same time.

Check this resource page and learn how to design the best dot plots that will impress your audience.
https://www.datylon.com/resources/chart-library/dot-plot

#### ❌ Bad choice: Grouped bar/column chart
![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/a4de05f9-a09b-4576-9733-7abd972cd928)
Grouped bar charts are usually based on the color differences of the bars of the same group. This makes it difficult to read for colorblind users. With a large number of categories, this chart becomes unreadable to everyone.

### Correlation charts
 

#### ✅ Good choice: Bubble chart
![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/bb5a95ad-d6ef-43af-84e1-e2a448f34089)

It can be easily used without color. X- and Y- axes, size, and different icons provide 4 dimensions already which is easily enough for most of the visualization tasks.

#### ❌ Bad choice: Heatmap

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/ce09ef28-43e6-4121-abd1-d5b2e8e2102a)

Heatmaps are heavily dependent on color, so the only way to make it safe for colorblind readers is to use one hue or grayscale palette.

### Part-to-whole & hierarchical charts

#### ✅ Good choice: Icon array

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/4b737d7f-2e05-4dec-b511-d23563d4d3a1)

Icon array is a rare case of a part-to-whole chart that doesn’t depend on colored areas or sectors. With the use of icons instead of color differentiation, this chart becomes a preferable chart type for colorblind people among all part-to-whole charts.

#### ❌ Bad choice: Treemap

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/5750f6dc-f98d-4ec0-8e15-be98c739235e)
Similar to heatmaps, treemaps are famous for their extensive use of color. Surely, a treemap can be made also with a mono hue palette or just with the help of stroke borders, but the lack of color will weaken its visual strength, especially if a complex hierarchical structure should be presented. One of the things that can save a treemap is spacing between cells.

### Date over time charts
 

#### ✅ Good choice: Line chart

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/2094bc73-e5e1-4edf-b1b7-dea6110d822d)

The simplest and most flexible temporal chart that can be modified in various ways to make it readable for a colorblind audience. In the case of multiple categories, the line width can be modified as well as various types of dashed strokes. Direct labels and data marks can also be used to differentiate lines.

https://www.datylon.com/resources/chart-library/line-chart

#### ❌ Bad choice: Streamgraph

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/b1e1b75f-270f-4bda-ba53-5b3e286c986b)

A very beautiful chart, but helpless without color. It loses its attractiveness and readability right away.

### Distribution
 

#### ✅ Good choice: Density and ridgeline plots

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/e7264565-0216-4670-bebb-f5058cba8142)
A good choice for visualizing both single and multiple distributions. Opacity and direct labels can substitute the need for coloring.

#### ❌ Bad choice: One-dimensional heatmap

![image](https://github.com/liubovkyry/DataVisualization/assets/118057504/a73f68f2-788d-4c0c-bd82-b656cfe7ceb0)
A one-dimensional heatmap can quickly become a bad choice if multiple colors are used. One hue palette can work pretty well though.
