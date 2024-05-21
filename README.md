# PhotoDigitizer
Photo_digitizer is a tool that calculates the ground coverage of annotated polygons from images based on the labelme annoation tool.

## Usage

### 1. Open the software Photo_digitizer

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure1.png)

### 2. In the Photo_digitizer software interface (as shown in the figure above), specify the data required by the calculation software

- Image Directory: Directory where images and json files are located.

- Elevation : Enter the elevation value of the annotated area.

- Data Format:  Data format for calculating image tiles.

- Camera Parameters, POS Directory: Provide if images do not contain them; otherwise, no need to provide (the figure below shows the case where camera parameters and POS directory are needed, format as follows).

 ![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure2.png)

  ![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure3.png)

### 3. Click to run and generate the result file. The result is in SHP data format with WGS84 geographic coordinates

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure4.png)

### 4. Import the results into ArcMap for editing and report generation.

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure5.png)

## Test data page

### 1. Image directory

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure6.png)

### 2. Image photo

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure7.png)

### 3. json

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure8.png)

### 4. Camera parameters

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure9.png)

### 5. POS

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure10.png)

## 4.Use Labelme software to annotate red tide

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure11.png)

