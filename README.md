# Plant Species Image Classification
## Laboratory Work 2-A Activity

### A. Project Overview
This project focuses on the development of a machine learning model designed to classify 20 different variants of Aglaonema. Aglaonemas are popular ornamental plants known for their diverse variegation patterns, ranging from deep greens to vibrant pinks and reds.

### Purpose: 
The goal is to evaluate how effectively an Image Classification model (trained via Teachable Machine) can distinguish between closely related cultivars that share similar leaf shapes but differ in color distribution and spotting patterns.

### B. Plant Species Section
# Aglaonema Varieties Dataset

| # | Common Name | Scientific Name / Cultivar | Distinctive Visual Description | Representative Image |
|---|-------------|----------------------------|--------------------------------|----------------------|
| 1 | Siam Aurora | *Aglaonema* 'Siam Aurora' | Green leaves with vibrant red/pink borders and midribs. | ![Siam Aurora](images/siam_aurora.jpg) |
| 2 | Suksom Jaipong | *Aglaonema* 'Suksom Jaipong' | Known for almost solid, glowing red leaves with very little green. | ![Suksom Jaipong](images/suksom.jpg) |
| 3 | Lady Valentine | *Aglaonema* 'Lady Valentine' | Rose-pink leaves splashed with dark green blotches and margins. | ![Lady Valentine](images/lady_valentine.jpg) |
| 4 | Silver Bay | *Aglaonema* 'Silver Bay' | Large, oval leaves with a broad, silvery-gray center and green edges. | ![Silver Bay](images/silver_bay.jpg) |
| 5 | Pictum Tricolor | *Aglaonema pictum* 'Tricolor' | A rare camouflage pattern consisting of three shades of green. | ![Pictum Tricolor](images/pictum.jpg) |
| 6 | Super White | *Aglaonema* 'Super White' | Pure creamy-white foliage with very thin green veins. | ![Super White](images/super_white.jpg) |
| 7 | Pink Dalmatian | *Aglaonema* 'Pink Dalmatian' | Deep green waxy leaves covered in bright pink polka dot spots. | ![Pink Dalmatian](images/dalmatian.jpg) |
| 8 | Maria | *Aglaonema* 'Maria' | Dense, dark green foliage with silver-green wavy markings. | ![Maria](images/maria.jpg) |
| 9 | Silver Queen | *Aglaonema* 'Silver Queen' | Narrow, lance-shaped leaves with heavy silver-gray variegation. | ![Silver Queen](images/silver_queen.jpg) |
| 10 | Red Anjamani | *Aglaonema* 'Red Anjamani' | Bright red leaves with a very thin dark green border. | ![Red Anjamani](images/anjamani.jpg) |
| 11 | White Rajah | *Aglaonema* 'White Rajah' | Elegant white-to-cream centers with green feathery edges. | ![White Rajah](images/white_rajah.jpg) |
| 12 | Emerald Bay | *Aglaonema* 'Emerald Bay' | Dark green edges with a muted smoky-silver center. | ![Emerald Bay](images/emerald_bay.jpg) |
| 13 | Anyanmee | *Aglaonema* 'Anyanmee' | High-contrast red and green patterns, often with speckled borders. | ![Anyanmee](images/anyanmee.jpg) |
| 14 | First Diamond | *Aglaonema* 'First Diamond' | Highly variegated white leaves with dark green flecks. | ![First Diamond](images/first_diamond.jpg) |
| 15 | Crete | *Aglaonema* 'Crete' | Green leaves with narrow fiery red edges and pink undersides. | ![Crete](images/crete.jpg) |
| 16 | Cochin | *Aglaonema* 'Cochin' | Rounder leaves with a blend of pink, cream, and green patches. | ![Cochin](images/cochin.jpg) |
| 17 | Sparkling Sarah | *Aglaonema* 'Sparkling Sarah' | Light green leaves with pink midribs and yellow-pink speckles. | ![Sparkling Sarah](images/sarah.jpg) |
| 18 | Valentine | *Aglaonema* 'Valentine' | Broad leaves with deep vibrant pink centers and green margins. | ![Valentine](images/valentine.jpg) |
| 19 | Black Lance | *Aglaonema* 'Black Lance' | Long pointed leaves with a silver center and very dark edges. | ![Black Lance](images/black_lance.jpg) |
| 20 | Prosperity | *Aglaonema* 'Prosperity' | Unique mix of pinkish-white centers and green marbling. | ![Prosperity](images/prosperity.jpg) |

Gemini said
Here is the full Step 9 formatted in Markdown. You can copy this directly into your README.md on GitHub.

I have integrated your specific list of 20 Aglaonema variants and organized everything into a professional, scannable layout.

Aglaonema Variants: Image Classification Project
Laboratory Work 2-A Activity — Plant Species Classification
A. Project Overview
This project involves the design and training of an image classification model to recognize 20 specific variants of Aglaonema (Chinese Evergreens). These plants are widely known for their diverse leaf variegation, ranging from camo-patterns to vibrant red and pink foliage.

Purpose: To develop a machine learning tool that can distinguish between closely related cultivars that share similar leaf shapes but vary significantly in color distribution, spotting, and margin patterns.

B. Plant Species Section
The following 20 Aglaonema variants were used for training. Each class contains 250+ images.

#	Common Name	Scientific Name / Cultivar	Distinctive Visual Description	Representative Image
1	Siam Aurora	Aglaonema 'Siam Aurora'	Green leaves with vibrant red/pink borders and midribs.	![Siam Aurora](images/1.jpg)
2	Suksom Jaipong	Aglaonema 'Suksom Jaipong'	Known for almost solid, glowing red leaves with very little green.	![Suksom Jaipong](images/2.jpg)
3	Lady Valentine	Aglaonema 'Lady Valentine'	Rose-pink leaves splashed with dark green blotches and margins.	![Lady Valentine](images/3.jpg)
4	Silver Bay	Aglaonema 'Silver Bay'	Large, oval leaves with a broad, silvery-gray center and green edges.	![Silver Bay](images/4.jpg)
5	Pictum Tricolor	Aglaonema pictum 'Tricolor'	A rare "camouflage" pattern consisting of three shades of green.	![Pictum Tricolor](images/5.jpg)
6	Super White	Aglaonema 'Super White'	Pure creamy-white foliage with very thin green veins.	![Super White](images/6.jpg)
7	Pink Dalmatian	Aglaonema 'Pink Dalmatian'	Deep green waxy leaves covered in bright pink "polka dot" spots.	![Pink Dalmatian](images/7.jpg)
8	Maria	Aglaonema 'Maria'	Dense, dark green foliage with silver-green wavy markings.	![Maria](images/8.jpg)
9	Silver Queen	Aglaonema 'Silver Queen'	Narrow, lance-shaped leaves with heavy silver-gray variegation.	![Silver Queen](images/9.jpg)
10	Red Anjamani	Aglaonema 'Red Anjamani'	Bright red leaves with a very thin, dark green border.	![Red Anjamani](images/10.jpg)
11	White Rajah	Aglaonema 'White Rajah'	Elegant white-to-cream centers with green feathery edges.	![White Rajah](images/11.jpg)
12	Emerald Bay	Aglaonema 'Emerald Bay'	Dark green edges with a muted, smoky-silver center.	![Emerald Bay](images/12.jpg)
13	Anyanmee	Aglaonema 'Anyanmee'	High-contrast red and green patterns, often with speckled borders.	![Anyanmee](images/13.jpg)
14	First Diamond	Aglaonema 'First Diamond'	Highly variegated white leaves with dark green flecks.	![First Diamond](images/14jpg)
15	Crete	Aglaonema 'Crete'	Green leaves with narrow, fiery red edges and pink undersides.	![Crete](images/15.jpg)
16	Cochin	Aglaonema 'Cochin'	Rounder leaves with a blend of pink, cream, and green patches.	![Cochin](images/16.jpg)
17	Sparkling Sarah	Aglaonema 'Sparkling Sarah'	Light green leaves with pink midribs and yellow-pink speckles.	![Sparkling Sarah](images/17.jpg)
18	Valentine	Aglaonema 'Valentine'	Broad leaves with deep, vibrant pink centers and green margins.	![Valentine](images/18.jpg)
19	Black Lance	Aglaonema 'Black Lance'	Long, pointed leaves with a silver center and very dark edges.	![Black Lance](images/19.jpg)
20	Prosperity	Aglaonema 'Prosperity'	Features a unique mix of pinkish-white centers and green marbling.	![Prosperity](images/20.jpg)

### C. Model Training Details
The model was trained using the Standard Image Model architecture.

Epochs: 100
- I chose **100 epochs** so the model has enough training cycles to learn patterns from the dataset and improve its accuracy. This value allows the model to update its weights multiple times while keeping the training time reasonable. It is also a common starting point in many machine learning experiments.

Batch Size: 16

Learning Rate: 0.001

Images per Class: 250

### Screenshot of the training settings
<img width="1522" height="815" alt="image" src="https://github.com/user-attachments/assets/e5e5154d-dfd3-4358-877b-f4500b9da2ac" />

### D. Model Evaluation
The following metrics were captured from the "Under the Hood" section of Teachable Machine.

#### Confusion Matrix
<img width="382" height="756" alt="image" src="https://github.com/user-attachments/assets/2ddad6c9-a318-40aa-86da-ac3466f65648" />

#### Accuracy Per Class
<img width="377" height="786" alt="image" src="https://github.com/user-attachments/assets/ea126a4b-5f11-4299-bc14-d8f69579014a" />

#### Accuracy per Epoch
<img width="368" height="602" alt="image" src="https://github.com/user-attachments/assets/3e377861-23d2-4d19-a454-fb388a4793c8" />

### E. Model Testing
##1. 
### Input image : Anyanmee
### Predicted plant class : Anyanmee, Silver Bay, Prosperity
### Confidence Score: 53%
<img width="305" height="517" alt="image" src="https://github.com/user-attachments/assets/13bcbc8b-3fa3-4984-b0d3-cf1116fa5362" />
<img width="361" height="857" alt="image" src="https://github.com/user-attachments/assets/a06c74da-0e67-4bdf-b255-3a880ba6bde5" />

##2.
### Input image : Black Lance
### Predicted plant class : Black Lance
### Confidence Score: 100%
<img width="387" height="627" alt="image" src="https://github.com/user-attachments/assets/934f3470-0e4d-4a95-af8f-d273f1cbf2ff" />
<img width="376" height="881" alt="image" src="https://github.com/user-attachments/assets/6caeaa38-f123-46e7-8a53-47c09f046f88" />

##3.
### Input image : Cochin
### Predicted plant class : Cochin
### Confidence Score: 100%
<img width="347" height="562" alt="image" src="https://github.com/user-attachments/assets/7b5aa7e4-7789-4af9-af07-aa7f67f5311d" />
<img width="311" height="831" alt="image" src="https://github.com/user-attachments/assets/68452399-863f-4dfd-99c5-880212a5e704" />

##4.
### Input image : Crete
### Predicted plant class : Crete
### Confidence Score: 100%
<img width="392" height="671" alt="image" src="https://github.com/user-attachments/assets/0b432fd4-4cf2-4473-9b88-e9557a051111" />
<img width="321" height="876" alt="image" src="https://github.com/user-attachments/assets/a7b64ba3-78ac-4db4-a806-6f1e03de3317" />

##5.
### Input image : Emerald Bay
### Predicted plant class : Emerald Bay, Silver Bay
### Confidence Score: 99%
<img width="423" height="891" alt="image" src="https://github.com/user-attachments/assets/434205ca-de9b-4378-9b9f-5a6fa6dbe6c6" />

##6.
### Input image : First Diamond
### Predicted plant class : First Diamond
### Confidence Score: 99%
<img width="526" height="443" alt="image" src="https://github.com/user-attachments/assets/7e85d677-e41f-4b72-abb3-e77ea3a15d77" />
<img width="352" height="758" alt="image" src="https://github.com/user-attachments/assets/3a4be964-453d-45d9-9c50-5b914712d597" />

##7.
### Input image : Lady Valentine
### Predicted plant class : Lady Valentine, Valentine
### Confidence Score: 78%
<img width="375" height="362" alt="image" src="https://github.com/user-attachments/assets/fd467e35-9801-4aca-84b3-266ca1d88c1b" />
<img width="303" height="882" alt="image" src="https://github.com/user-attachments/assets/e567561f-095e-460e-8d5b-c590092d7238" />

##8.
### Input image : Maria
### Predicted plant class : Maria
### Confidence Score: 100%
<img width="303" height="330" alt="image" src="https://github.com/user-attachments/assets/03093418-9b4d-4bf2-a5fb-937741c5c796" />
<img width="305" height="787" alt="image" src="https://github.com/user-attachments/assets/b2c8d6c8-2b30-4865-9d27-51339316db51" />

##9.
### Input image : Pictum Tricolor
### Predicted plant class : Pictum Tricolor, Anyanmee
### Confidence Score: 71%
<img width="328" height="297" alt="image" src="https://github.com/user-attachments/assets/d0e91be5-38b0-4bd0-981d-2059da63fb2d" />
<img width="312" height="768" alt="image" src="https://github.com/user-attachments/assets/21e6da80-48aa-456d-81fd-551348f69d7f" />

##10.
### Input image : Siam Aurora
### Predicted plant class : Siam Aurora
### Confidence Score: 100%
<img width="278" height="413" alt="image" src="https://github.com/user-attachments/assets/b965fca2-f70b-4c96-bb1d-2ad1c21f46cb" />



