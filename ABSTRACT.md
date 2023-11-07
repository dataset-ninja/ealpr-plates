**EALPR: Egyptian Automatic License Plate Recognition (Plates)** is a comprehensive dataset tailored for object detection tasks, particularly focused on the recognition and localization of diverse characters found on license plates. Comprising 2068 images, the dataset encompasses a substantial 10797 annotated objects, spread across 27 distinct classes, including characters like *١*, *م*, *أ*, among others such as *٦*, *س*, *ر*, and a variety of Arabic characters. The dataset showcases the versatility of characters present on license plates, especially exemplified by the Egyptian License Plate (LP), which typically incorporates Arabic digits and characters. This rich collection captures the variation in characters utilized on plates from different regions, including those that use Latin letters, such as Europe, Brazil, and the US, thereby serving as a valuable resource for training models to recognize and interpret diverse international license plate characters.

## EALPR Structure

- EALPR: Vehicles [(available on DatasetNinja)](https://datasetninja.com/ealpr-vehicles)
- EALPR: Plates (current)

<img src="https://i.ibb.co/BNjRwgR/Screenshot-2023-10-30-151153.png" alt="image" width="400">

<span style="font-size: smaller; font-style: italic;">EALPR: Vehicles demo.</span>

<img src="https://i.ibb.co/brTZ8NC/Screenshot-2023-10-30-151206.png" alt="image" width="400">

<span style="font-size: smaller; font-style: italic;">EALPR: Plates demo.</span>

## Proposed method

Authors use two object detection models for license plate detection and recognition. The input to authors' proposed system is the vehicle image, whereas the output is the recognized license plate characters and digits. Tiny-YOLOV3 is the backbone architecture for both stages LP detection and recognition.

<img src="https://i.ibb.co/D8B8sBh/Screenshot-2023-10-30-145453.png" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Main Stages of the Proposed EALPR Approach.</span>

## About EALPR

Authors scrap the EALPR dataset images from websites such as Instagram pages and Facebook Marketplace using web scraping Tools. It has 2,450, and 12,160 characters images including many types of vehicles such as cars, buses, trucks, microbuses, and mini-busses. The vehicle images are captured using different cameras, at varying times, lighting, and background. 

<img src="https://i.ibb.co/tx3gwCz/Screenshot-2023-10-30-150107.png" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Characters and Digits Statistics in the EALPR Dataset.</span>

The Egyptian License Plate (LP) uses the Arabic digits and characters which is varying in several countries that use Latin letters such as Europe, Brazil, US, ... etc. It has a dimension 16 (height) X 40 (width) with aspect ratio 1:2 approximately. its layout is divided into 3 regions: the country region contains the Egypt word in Arabic and English format, the character region includes plate characters, and the number region contains plate digits. Egyptian License Plate structure uses 10 Arabic digits and 17 Arabic characters.

<img src="https://i.ibb.co/0Jb9NqC/Screenshot-2023-10-30-150456.png" alt="image" width="400">

<span style="font-size: smaller; font-style: italic;">Egyptian License Plate Structure.</span>

<img src="https://i.ibb.co/x6Q65PD/Screenshot-2023-10-30-150910.png" alt="image" width="400">

<span style="font-size: smaller; font-style: italic;">Plate Arabic Digits and Latin Digits.</span>

<img src="https://i.ibb.co/Pc3Ljny/Screenshot-2023-10-30-150925.png" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Plate Arabic Characters and Latin Characters.</span>

After collecting EALPR dataset authors manually annotate the vehicles, characters, and digits using [Ybat tool](https://github.com/drainingsun/ybat).
