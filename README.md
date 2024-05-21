# PhotoDigitizer
photo_digitizer is a tool that calculates based on images annotated with labelme. It reads JSON data and converts two-dimensional data into three-dimensional geographic coordinates SHP data.

## Usage

The scripts to run the whole process of the ParallelSfM are given:

### 1. Open the calculation software Photo_digitizer

![](\figures\figure1.png)

### 2. In the Photo_digitizer software interface (as shown in the figure above), input the data required by the calculation software

- Image Directory: Directory where images and json files are located.

- Elevation Retrieval: Enter the elevation value of the annotated area.

- Data Format:  Data format for calculating image tiles.

- Camera Parameters, POS Directory: Provide if images do not contain them; otherwise, no need to provide (the figure below shows the case where camera parameters and POS directory are needed, format as follows).

  ![](\figures\figure2.png)

  ![](\figures\figure3.png)

### 3. Click to run and generate the result file. The result is in SHP data format with WGS84 geographic coordinates

![](\figures\figure4.png)

### 4. Import the results into ArcMap for editing and report generation.

![](\figures\figure5.png)

## Test data page

### 1. Image directory

![](\figures\figure6.png)

### 2. Image photo

![](\figures\figure7.png)

### 3. json

![](\figures\figure8.png)

### 4. Camera parameters

![](\figures\figure9.png)

### 5. POS

![](\figures\figure10.png)

## 4.Use Labelme software to annotate red tide

![](/figures/figure11.png)

