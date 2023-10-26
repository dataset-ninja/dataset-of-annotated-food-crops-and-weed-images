The **Dataset of Annotated Food Crops and Weed Images** offers a comprehensive look at food crops and weeds in their early seedling stages. With 1,118 images and 7,853 manual annotations, it neatly classifies them into two primary categories: *weed* and *crop*. The dataset was collected in several locations in Latvia and describes eight weed and six food species.

The species of the food crops were chosen based on their popularity among consumers in Latvia and the necessity to implement intensive weed management solutions. Two types of images are included in data set: images of food crops and weeds that have been cultivated in vegetation pots in controlled greenhouse conditions; images of food crops and weeds from open field conditions. Images of plants from greenhouse were taken at the Scientific Institute for Plant Protection Research “Agrihorts”, University of Life Sciences and Technologies of Latvia, Jelgava, Latvia. Images from field conditions are from three locations in Latvia: Kekava, Rujiena, and Krimulda. The digital images were captured with perspective projection over plants.

To build the dataset, common weed species found in vegetable fields were selected, 8 weeds: goosefoot (Chenopodium album), catchweed (Galium aparine), field pennycress (Thlaspi arvense), shepherd’s purse (Capsella bursa-pastoris), field chamomile (Matricaria perforata), wild buckwheat (Polygonum convolvulus), field pansy (Viola arvensis), quickweed (Galinsoga parviflora). There were 6 food crops selected: beetroot (Beta vulgaris), carrot (Daucus carota var. sativus), zucchini (Cucurbita pepo subsp. pepo), pumpkin (Cucurbita pepo), radish (Raphanus sativus var. sativus), black radish (Raphanus sativus var. niger). 

| Abbreviation | Taxonomic classification | Family       | Common name        | Class |
|--------------|-------------------------|--------------|--------------------|-------|
| CA           | Chenopodium album L.   | Amaranthaceae | Goosefoot Weed     | Weed  |
| GA           | Galium aparine          | Rubiaceae     | Catchweed Weed     | Weed  |
| TA           | Thlaspi arvense         | Brassicaceae  | Field pennycress    | Weed  |
| CB           | Capsella bursa-pastoris | Brassicaceae  | Shepherd's purse    | Weed  |
| MI           | Matricaria perforata    | Asteraceae   | Field chamomile     | Weed  |
| PC           | Polygonum convolvulus   | Polygonaceae  | Wild buckwheat     | Weed  |
| VA           | Viola arvensis          | Violaceae    | Field pansy        | Weed  |
| GP           | Galinsoga parviflora    | Asteraceae   | Quickweed          | Weed  |
| BV           | Beta vulgaris           | Amaranthaceae | Common beet        | Crop  |
| DC           | Daucus carota var. sativus | Apiaceae  | Carrot              | Crop  |
| CPS          | Cucurbita pepo subsp. pepo | Cucurbitaceae | Zucchini          | Crop  |
| CP           | Cucurbita pepo          | Cucurbitaceae | Pumpkin            | Crop  |
| RSS          | Raphanus sativus var. sativus | Brassicaceae | Radish         | Crop  |
| RSN          | Raphanus sativus var. niger | Brassicaceae | Black radish   | Crop  |

<span style="font-size: smaller; font-style: italic;">List of food crops and weed species available in the dataset.</span>

In a greenhouse, plants were grown in vegetation pots under natural and artificial light. The peat substrate was used for soil preparation with such characteristics: pH 6.0, moisture content <65%, peat fraction <20.0 mm, N 12.0%, P₂O₅ 14.0%, K₂O 24.0%, Te 1.0 kg m³. In each vegetation pot, the seeds of the plants were sown in one to two rows at a distance between them of 2.0 – 5.0 cm. The seedling boxes were watered once to twice per week. Temperature was set to +20.0 °C daytime (8:00 a.m. – 8:00 p.m.), and +15.0 °C during the night (8:00 p.m. – 8:00 a.m.), humidity <50%. Additional to natural light, LED lamps (Philips Lightning IBRS, 180W) were used for plant cultivation with illumination period from 6:00 a.m. – 8:00 p.m. Photos of vegetation boxes were taken with additional light and a three-point supporting photostat. A distance of 30 cm was set from the lens of the camera to the surface of the vegetation box. Once a day, images of plants were taken starting from the first stage of the plant development.

Canon EOS 800D and Sony W800 digital cameras and Intel RealSense D435 cameras were used to take photos. An Intel RealSense D435 camera and Sony W800 digital camera were used to acquire images in field conditions, but Canon EOS 800D digital camera was used in a controlled environment.

Images of plants in field conditions were taken in the organic vegetable farms in three locations specified above before weeding activities carried out by farmers. To capture images a platform mounted on four wheels was constructed. A digital camera was attached in the middle of the platform with the lens directed downwards. The platform was moved across the field in different directions to take photos of the plants. Afterwards, weeds and crops at early growth stages were manually marked in the pictures with ground truth bounding boxes. All raw images were annotated by human experts.
