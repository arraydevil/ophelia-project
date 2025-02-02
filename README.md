# ophelia-project
Despite the advances in pharmochemicals in the cosmetic industry and the wide range of brands and prices available to a wider audience, the offer of beauty products remains limited in terms of diversity. This scenario directly reflects a series of social constructions, often biased and discriminatory, of which the beauty market is both hostage and perpetuator. An example of this is how people with darker skin tones face greater difficulty in finding products that fit their needs appropriately. Ignored despite being a relevant percentage of potential consumers, the population not covered by the available options is proof of the persistence of a retrograde mentality that, by neglecting color variability, contradicts the fundamental purpose of makeup, the promotion of self-esteem and well-being.
The Facial Recognition and Makeup Recommendation System Ideal for Different Skin Tones arose from the realization of this lack in the offer of varied shades. This project seeks to address this gap, bringing a solution that expands the options available for all skin types, promoting greater inclusion and representativeness in the cosmetics market.

![1](https://github.com/user-attachments/assets/b734ce41-f4b8-41cb-b21a-6b0b5ac22a5c)
The overall goal of this project is to develop an automated facial recognition system that, through image analysis, can identify different skin tones and suggest makeup products that best suit each shade. The system seeks to increase inclusion within the market, ensuring that consumers of all skin tones can find products that suit their needs. In addition, it is intended to create a database of skin tones and matching products that can be used by developers and companies in the beauty sector to improve the diversity of their offerings.
![17](https://github.com/user-attachments/assets/e97e8b12-dbf5-471a-bcd9-94aad5c20bc4)

The graphics libraries used include OpenCV, for image processing and manipulation, and NumPy, for mathematical operations and array manipulation. In addition, Google Colab tools were used to upload and display images. The structuring of the project followed a sequence of well-defined steps. In the Initialization stage, he performed the configuration of the work environment and the import of the necessary libraries. 
![5](https://github.com/user-attachments/assets/edc95e12-ec0a-4112-a1f6-18c1afbaab11)
The Image Processing step involved converting the image to the HSV color space and applying a mask for skin segmentation. In Face Detection, the Haar Cascade classifier was used to detect faces in the segmented image. Subsequently, in the Calculation of Average Skin Color, the average skin color of the detected faces was calculated and converted to hexadecimal format.
![11](https://github.com/user-attachments/assets/3943287f-2615-4e1c-8257-fa89e555a876)
During the Skin Color Classification, the average color was compared with a predefined color chart to determine the skin color category. Finally, in the Product Association, the skin color category was mapped to a corresponding product link.
![13](https://github.com/user-attachments/assets/9df8e5d9-6ad4-42fb-b9f1-e105a1fb6727)
- Reading and conversion of image of RGB for HSV.
- Creates and applies a "mascara" for a skin area segmentation.
- Converts the segmentational image for grey scale.
- Haar classifier to detect faces in the grey scale.
![16](https://github.com/user-attachments/assets/86818f12-0c07-41c2-b65c-9a58fef76885)
- Converts medium color to RGB and hexadecimal.
- Determines the skin color category and gets the recommended a comestic link.

