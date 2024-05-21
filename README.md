# PhotoDigitizer
Photo_digitizer is a tool that calculates the ground coverages of annotated polygons from images. The annotated polygons are drawn from the labelme annoation tool. Based on the principle of triangulation, the software can calculate the 3D geographical coordinates of annotated polygons by using intrinc and extrinsic data from image EXIF or specified by users. In this study, this tool has been used for red tide monitoring by using UAV images.

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/Figure0.png)

## Usage

### 0. Use Labelme software to annotate red tide

![](https://github.com/json87/PhotoDigitizer/blob/main/figures/figure11.png)

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

## Reference

Please refer to the following papers for the technique details.

```
@article{
  title={UAV Photogrammetry for Red Tide Monitoring and Geo-Localization via Onboard GNSS/IMU Data},
  author={Mengran Yang, Yichen Ma, San Jiang, Cheng Yin and Wei Huang},
  journal={Geocarto International },
  pages={1--22},
  year={2024},
  publisher={Taylor & Francis}
}
