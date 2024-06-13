# pycine_calculate_velocity

This repository provides a Jupyter Notebook for extracting and displaying basic metadata from `.cine` files using the `pycine` library. The notebook demonstrates how to read a `.cine` file, access its metadata, and display key parameters.

## Overview

The Jupyter Notebook in this repository performs the following tasks:

1. Reads the header information of a `.cine` file using the `pycine` library.
2. Calculate velocity from arrow in `.cine` file.
3. Extracts various metadata fields from the `.cine` file.
4. Displays the extracted metadata in a structured format.

## Metadata Table

The following table maps the metadata parameters extracted from the `.cine` file using `pycine` to their corresponding values:

| Parameter                              | Value Description                     |
|----------------------------------------|----------------------------------------|
| `header.cinefileheader.Type`           | Type of cine file                     |
| `header.cinefileheader.Headersize`     | Size of the header                    |
| `header.cinefileheader.Compression`    | Compression type                      |
| `header.cinefileheader.Version`        | Version of the cine file              |
| `header.cinefileheader.FirstMovieImage`| First movie image offset              |
| `header.cinefileheader.TotalImageCount`| Total number of images                |
| `header.cinefileheader.FirstImageNo`   | First image number                    |
| `header.cinefileheader.ImageCount`     | Number of images                      |
| `header.cinefileheader.OffImageHeader` | Offset to image header                |
| `header.cinefileheader.OffSetup`       | Offset to setup                       |
| `header.cinefileheader.OffImageOffsets`| Offset to image offsets               |
| `header.cinefileheader.TriggerTime`    | Trigger time                          |
| `header.bitmapinfoheader.biSize`       | Size of the bitmap info header        |
| `header.bitmapinfoheader.biWidth`      | Width of the bitmap                   |
| `header.bitmapinfoheader.biHeight`     | Height of the bitmap                  |
| `header.bitmapinfoheader.biPlanes`     | Number of planes                      |
| `header.bitmapinfoheader.biBitCount`   | Bit count                             |
| `header.bitmapinfoheader.biCompression`| Compression type                      |
| `header.bitmapinfoheader.biSizeImage`  | Size of the image                     |
| `header.bitmapinfoheader.biXPelsPerMeter`| Pixels per meter (X axis)           |
| `header.bitmapinfoheader.biYPelsPerMeter`| Pixels per meter (Y axis)           |
| `header.bitmapinfoheader.biClrUsed`    | Number of colors used                 |
| `header.bitmapinfoheader.biClrImportant`| Number of important colors           |
| `header.setup.FrameRate`               | Frame rate of the cine file           |
| `header.setup.Shutter`                 | Shutter speed                         |
| `header.setup.PostTrigger`             | Post trigger                          |
| `header.setup.FrameDelay`              | Frame delay                           |
| `header.setup.AspectRatio`             | Aspect ratio                          |
| `header.setup.ImWidth`                 | Image width                           |
| `header.setup.ImHeight`                | Image height                          |
| `header.setup.Serial`                  | Serial number                         |
| `header.setup.Saturation`              | Saturation level                      |
| `header.setup.AutoExposure`            | Auto exposure setting                 |
| `header.setup.CameraVersion`           | Camera version                        |
| `header.setup.FirmwareVersion`         | Firmware version                      |
| `header.setup.SoftwareVersion`         | Software version                      |
| `header.setup.RecordingTimeZone`       | Recording time zone                   |
| `header.setup.CFA`                     | Color Filter Array                    |
| `header.setup.Bright`                  | Brightness level                      |
| `header.setup.Contrast`                | Contrast level                        |
| `header.setup.Gamma`                   | Gamma value                           |
| `header.setup.AutoExpLevel`            | Auto exposure level                   |
| `header.setup.AutoExpSpeed`            | Auto exposure speed                   |
| `header.setup.Rotate`                  | Rotation setting                      |
| `header.setup.RealBPP`                 | Real bits per pixel                   |
| `header.setup.Conv8Min`                | Minimum 8-bit conversion              |
| `header.setup.Conv8Max`                | Maximum 8-bit conversion              |
| `header.setup.BlackLevel`              | Black level                           |
| `header.setup.WhiteLevel`              | White level                           |


