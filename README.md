# CNN-rgbUAV
Using CNN (convolutional neural networks) to map forest tree species in high resolution UAV-based RGB-imagery.

<details>

<summary>Architecture of CNN U-Net Credits</summary>
 

**Mapping forest tree species in high resolution UAV-based RGB-imagery by means of convolutional neural networks**,

Felix Schiefer, Teja Kattenborn, Annett Frick, Julian Frey, Peter Schall, Barbara Koch, Sebastian Schmidtlein,

ISPRS Journal of Photogrammetry and Remote Sensing, Volume 170, 2020, Pages 205-215, ISSN 0924-2716,

[Link](https://doi.org/10.1016/j.isprsjprs.2020.10.015)

**Abstract**: 
The use of unmanned aerial vehicles (UAVs) in vegetation remote sensing allows a time-flexible and cost-effective acquisition of very high-resolution imagery. Still, current methods for the mapping of forest tree species do not exploit the respective, rich spatial information. Here, we assessed the potential of convolutional neural networks (CNNs) and very high-resolution RGB imagery from UAVs for the mapping of tree species in temperate forests. We used multicopter UAVs to obtain very high-resolution (<2 cm) RGB imagery over 51 ha of temperate forests in the Southern Black Forest region, and the Hainich National Park in Germany. To fully harness the end-to-end learning capabilities of CNNs, we used a semantic segmentation approach (U-net) that concurrently segments and classifies tree species from imagery. With a diverse dataset in terms of study areas, site conditions, illumination properties, and phenology, we accurately mapped nine tree species, three genus-level classes, deadwood, and forest floor (mean F1-score 0.73). A larger tile size during CNN training negatively affected the model accuracies for underrepresented classes. Additional height information from normalized digital surface models slightly increased the model accuracy but increased computational complexity and data requirements. A coarser spatial resolution substantially reduced the model accuracy (mean F1-score of 0.26 at 32 cm resolution). Our results highlight the key role that UAVs can play in the mapping of forest tree species, given that air- and spaceborne remote sensing currently does not provide comparable spatial resolutions. The end-to-end learning capability of CNNs makes extensive preprocessing partly obsolete. The use of large and diverse datasets facilitate a high degree of generalization of the CNN, thus fostering transferability. The synergy of high-resolution UAV imagery and CNN provide a fast and flexible yet accurate means of mapping forest tree species.

**Keywords**: 
Deep learning; Forest inventory; Convolutional neural networks; Tree species classification; Unmanned aerial systems; Temperate forests
</details>
