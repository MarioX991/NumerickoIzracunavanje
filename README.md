
  <h1 align="center">  </h1>

  <p align="center">
    Studentski projekat sa kursa Numericko izracinavanje: Autonomous driving car
    <br />
   
 <!-- O Projektu -->
## O Projektu

Ovaj projekat je vezan za detekciju linija (traka) na putu i merenje zakrivljenosti kao i odstupanje auta od središta između dve linije. Sam projekat je pratio:
> <a href="https://chatbotslife.com/advanced-lane-line-project-7635ddca1960" > "Advanced Lane Line Project", Arnaldo Gunzi </a>

U samom papiru autor nas upoznaje sa osnovama vaznim za koncepte:

- Distorzija i kalibracija kamere
- Paletama boja RGB, HSV,  HVL
- Sobel operatorima, magnitudi gradijenta i orjetacija gradijenta (Gradient orientation)
- Perspective Transform (Bird's-eye view)
- Izolacija piksela potrebnih za detekciju leve i desne trake
- Računanje zakrivljenosti linije

Na samom kraju implementiramo gore navedene elemente na  realnom [snimku voznje na autoputa](https://raw.githubusercontent.com/udacity/CarND-Vehicle-Detection/master/project_video.mp4), dok je za kalibraciju kamere korišcen [obrazac](https://docs.opencv.org/2.4/_downloads/pattern.png).

<!-- Potrebne biblioteke  -->
## Potrebne biblioteke

* [Python 3.7](https://www.python.org/).
* [Anaconda](https://www.anaconda.com/), [The Jupyter Notebook](https://jupyter.org/), [Google colab](https://colab.research.google.com/notebooks/intro.ipynb).
* [OpenCv](https://opencv.org/).
* Ostali paketi koji su korisceni [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/),[moviepy](https://pypi.org/project/moviepy/) .

<!-- NOTES -->
## Notes

* Postoji dosta  prostora za unapređenje projekta, neosporni su problemi koji nastaju usled pojavljivanja senki na put kao i usled nedostataka adekvatne obeleženosti puta koje stvaraju probleme pri samom detekciji linija.
* Takode projekat se može unaprediti da pored detekcije linija detektuje i meri rastojanja od odstalih automobile koji se nalaze na istom putu. Naravno i detekcija saobraćajnih znakove, na osnovu kojih bi moglo da se prati ograničenje brzine. 



<!-- REFERENCES -->
## References

* Papir : <a href="https://chatbotslife.com/advanced-lane-line-project-7635ddca1960" > "Advanced Lane Line Project", Arnaldo Gunzi </a>
* Papir: <a href="https://www.slideshare.net/BillKromydas/advanced-lane-finding" > "Advanced Lane Finding",  Bill Kromydas </a>
* Papir: <a href="https://www.fer.unizg.hr/_download/repository/Kosanovic_Marko.pdf" > "Metde kalibracije kamera",  Kosanovic Marko </a>
* Video : <a href="https://www.youtube.com/watch?v=lOEBsQodtEQ" > "Edge Detection Using Gradients",  Shree K. Nayar, Columbia University </a>
  
<!-- AUTHOR-->
## Autor
Marinko Kovačević

