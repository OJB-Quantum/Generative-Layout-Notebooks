# Generative-Layout-Notebooks
GDSII/OASIS layout generation done completely in Google Colab notebooks. Layout previews are plotted as 2D graphics before exporting. The notebooks are authored by Onri Jay Benally.

No need to download anything manually, just run the notebooks.

Note: This repository also contains some interesting fractal design layouts.

Here is a online rendered view of the notebooks: [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/OJB-Quantum/Generative-Layout-Notebooks/tree/main/)

Majority of the code used in this repository uses:
- [GDSTK](https://heitzmann.github.io/gdstk/gettingstarted.html)
- [numpy](https://numpy.org)
- [matplotlib](https://matplotlib.org)

Notes on Self-Avoiding Curve or Self-Avoiding Fractal Curve (Sometimes Called Non-Overlapping Fractal Curve): 
- Doesn't always have to fill space (evenly). 
- Emptier space in the middle of a large self-avoiding curve allows for less static build-up of electrical charge towards the center of the design.
- Never overlaps on the same layer.
- Can be implemented with complementary self-avoiding curves for scalable array of cells.
- You can also check out some interesting self-avoiding fractals here on Jeffrey Ventrella's webpage: http://www.fractalcurves.com/familytree/4.html

![unnamed](https://github.com/user-attachments/assets/b75e9abc-a477-4e28-b51d-3f6a6e391829)

> Borrowed from: J. Ventrella, “Chapter 4,” *The Family Tree of Fractal Curves* [Online].  
Available: http://www.fractalcurves.com/familytree/4.html.  

---
### Below are some screenshot examples of the Python plotted previews, followed by the GDS outputs:

<img width="5048" height="auto" alt="image" src="https://github.com/user-attachments/assets/70eee154-abcd-4349-b706-0e0db173f247" />

![CPW Chip 001](https://github.com/user-attachments/assets/e8e0ee21-a4e5-4349-a084-b252daf7ad55)

![CPW Chip 003](https://github.com/user-attachments/assets/200dd718-0b7c-49b2-89cf-a13ade46fdd0)

![CPW Chip 002](https://github.com/user-attachments/assets/4f3f01d6-2386-4377-a43f-71945412eebf)

![CPW Chip 004](https://github.com/user-attachments/assets/c60dc36a-1aeb-47a0-a5be-764f6969a957)

![Untitled](https://github.com/user-attachments/assets/dd77a00b-db61-4389-b1dc-a9404e1f1725)

![451532694-4b01e5aa-ee34-4dcb-afb1-98a5c1e73ab2](https://github.com/user-attachments/assets/0a038847-e73e-4a78-b89d-ce68ac865c29)

![Untitled](https://github.com/user-attachments/assets/6f47c2bc-ddd7-45c9-84d1-40686095f1d5)

![file](https://github.com/user-attachments/assets/a1a4c68e-f5ad-4999-a9ea-a365c2569019)


![Untitled](https://github.com/user-attachments/assets/23d94397-67ee-4c0d-a6ff-5604bd7897df)

![file](https://github.com/user-attachments/assets/ee03bebd-dc7a-468c-86ce-e8d2d11d361c)


![Untitled](https://github.com/user-attachments/assets/2b7b9b27-eec2-40ad-b840-6ea9612fc35d)

![file](https://github.com/user-attachments/assets/465e169c-f214-4eba-a7cd-85fbbfa807ef)

![Untitled](https://github.com/user-attachments/assets/3b2dd6a7-814d-4e1b-abfd-d47cb51b74fc)

![file](https://github.com/user-attachments/assets/b75ba2ed-ed5a-4a0f-8812-a18d399bd67b)



![Untitled](https://github.com/user-attachments/assets/2c451882-4bb2-4d39-9812-3ae590752404)


![file](https://github.com/user-attachments/assets/31a5f728-a4ca-4b40-8da8-b4487d3f5231)

![Untitled](https://github.com/user-attachments/assets/f6fee5b1-2bf6-4193-b75b-f93a11f394c8)


![file5](https://github.com/user-attachments/assets/bbad1bc8-0ab7-4c5f-9c82-d4955beb5621)

![Untitled](https://github.com/user-attachments/assets/df5ed1c5-03da-4d55-9e7a-04ed6d2ef4da)

![file](https://github.com/user-attachments/assets/84715e6a-ee03-472a-bf6e-7bad8cb29275)

![Untitled](https://github.com/user-attachments/assets/cd465306-61b2-4ead-a2d7-b911c4c370a1)

![file](https://github.com/user-attachments/assets/f12fa2e5-8016-42ef-b1bc-f3cc0fb4482e)


![HCF 001](https://github.com/user-attachments/assets/7b4c8354-4361-4347-a872-b064483bdebf)

![HCF 002](https://github.com/user-attachments/assets/23231a54-5ad1-424d-a99b-b0f015e2d29a)


![FWF 002](https://github.com/user-attachments/assets/b11879b3-e017-4157-bb2a-e4dae9f588d2)

![FWF 004](https://github.com/user-attachments/assets/49b5d4a0-d15f-46f6-a0db-550e4a01f7f0)

![FWF 001](https://github.com/user-attachments/assets/ffc1f102-5382-4059-bc8c-6d037bdd2e4a)

![file6](https://github.com/user-attachments/assets/4857b2d2-fe9e-4658-b2f7-f347383eb59c)


![CHB 001](https://github.com/user-attachments/assets/d15ab485-17b7-4a20-bf2b-c336d17acc39)

![CHB 003](https://github.com/user-attachments/assets/c4ff9f10-e4c0-462d-99b0-0fb7b8949733)

![CHB 004](https://github.com/user-attachments/assets/cd3f5f4f-2014-4bcd-9f6d-d6524ac64e91)

![CHB 006](https://github.com/user-attachments/assets/b68c1ecc-990b-4e5a-8666-dc04e958445d)


![CHB 002](https://github.com/user-attachments/assets/4f7c87cf-a630-4bbd-913f-d00828b5f63d)

![file](https://github.com/user-attachments/assets/6eb4cb3e-b378-47e0-b2ba-fb2f58abfc2e)



