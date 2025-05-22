<div align="center">
  
# K-Vehicles: A Dataset for Vehicle Detection in Aerial Imagery
<!--[Leo Thomas Ramos](https://www.linkedin.com/in/leo-thomas-ramos/)\, [Henry Valesaca](https://ec.linkedin.com/in/henry-velesaca-lara/)\, [Ángel D. Sappa](https://es.linkedin.com/in/angel-sappa-61532b17) -->
</div>

<!-- This repository is the official Pytorch implementation for [SkyScenes](). -->

<!-- [![Website](https://img.shields.io/badge/Project-Website-orange)](https://hoffman-group.github.io/SkyScenes/) [![arXiv](https://img.shields.io/badge/arXiv-SkyScenes-b31b1b.svg)](#)  -->


<!-- [![Watch the Demo](./assets/robust_aerial_videos.mp4)](./assets/robust_aerial_videos.mp4) -->

<img src="./assets/teaser.png" width="100%"/>

## Announcements

K-Vehicles is under review <!--at []() ! 📣 -->

## About the project

We present K-Vehicles, a new dataset for vehicle detection in aerial imagery. It is built from high-resolution RGB images captured by a Cessna aircraft over diverse real-world environments, including highways, agricultural fields, and industrial zones. The dataset comprises 15,168 cropped images of 1,024x1,024 pixels, annotated manually across seven vehicle categories: truck, forklift, machinery, pickup, tractor, vehicle, and bus. It incorporates relevant challenges such as occlusion, scene clutter, intra-scene variation, and variable lighting conditions, making it suitable for training and evaluating object detection models in realistic scenarios.

### Paper

[#](#)

## Data set description

K-Vehicles dataset consists of 15,168 cropped images, each with a fixed resolution of 1024x1024 pixels. These patches were obtained from aerial images captured under diverse conditions. The dataset is split into training, validation, and test subsets following an 80-10-10 proportion, resulting in 12,134 images for training, and 1,517 images for both validation and test sets. Annotations were generated in YOLO format, with each object instance described by its class and normalized bounding box coordinates. In total, the dataset includes 63,233 annotated instances, distributed as follows: 50,993 in the training set, 5,961 in the validation set, and 6,279 in the test set. The summary of K-Vehicles is as follows:

| Split        | # Images   | 
|----------------|----------|
| Train       | 12,134   |
| Valid   | 1,517  |
| Test           | 1,517  |

## Dataset download

The dataset is available for download via IEEE DataPort [here](#).

## Benchmarking results

To assess the utility of K-Vehicles, we conduct a benchmarking study using four recent YOLO architectures, from YOLOv9 to YOLOv12.

| Model | Precision | Recall | mAP@50 | mAP@50:95 |  Speed   | Checkpoint |
|------|------|------|------|------|------|------|
| YOLOv9m   | 0.956   | 0.770   | 0.865   | 0.698   | 2.9   | Download |
| YOLOv10m   | B2   | C2   | D2   | E2   | Speed   | Download   |
| YOLOv11m   | B3   | C3   | D3   | E3   | Speed   | Download   |
| YOLOv12m  | B4   | C4   | D4   | E4   | Speed   | Download   |

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## License

Distributed under GNU General Public License v3.0. See `LICENSE` for more information.

## BibTex

If you find this dataset useful, please star ⭐️⭐️⭐️ our repo and cite our paper.

```
soon
```

