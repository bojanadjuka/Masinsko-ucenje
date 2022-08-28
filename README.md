
# Klasifikacija žanra filma na osnovu njegovog postera

U ovom radu predstavljen je rad ResNet mreža na problemu višeklasne
klasifikacije. Na postere filmova dimenzija 128x128 primenjene su
već istrenirane (pretrained) ResNet mreže u cilju dobijanja žanra
filma. Svaki film može imati više žanrova.
Korišćena baza podataka, [41K movie posters from IMDB](https://www.kaggle.com/datasets/dadajonjurakuziev/movieposter?resource=download), 
sadrži približno 42 hiljade linkova do postera filma, naslov, godinu izlaska
filma, ocenu kao i žanrove kojima ti filmovi pripadaju. Takođe,
u bazi se nalazi i 13 dodatnih kolona koje predstavljaju binarno 
iskodirane žanrove. Za potrebe ovog rada korišćeni su linkovi do
postera filma kao i pomenute kolone koje se odnose na žanr.



## Literatura

 - [Deep Residual Learning for Image Recognition; Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun](https://arxiv.org/pdf/1512.03385.pdf)
 - [Predicting Genre from Movie Posters; Gabriel Barney, Kris Kaya](https://cs229.stanford.edu/proj2019spr/report/9.pdf?fbclid=IwAR16buKK_018jmAH1XApf4gGpFsc0jj0ZbFi7kNHOxzTF1N8X8aTvCyccu4)
 - Deep Learning with Python, Francois Chollet, Manning, 2018
 - [Visualizing the Loss Landscape of Neural Nets; Hao Li, Zheng Xu, Gavin Taylor, Christoph Studer, Tom Goldstein](https://arxiv.org/pdf/1712.09913.pdf)


## Autor

- Bojana Đuka

