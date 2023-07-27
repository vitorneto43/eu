# eu
Visão Computacional - Histograma para imagens cinza, neste foi feito com uma imagem RGB Cinza.

O primeiro passo foi baixar as bibliotecas.
Matplotlib
Open CV
e Numpy

após trouxe a imagem
img = cv.imread("Cinza.jpg")
e depois colocou a mostra
plt.imshow(img)

Por último colocou como Histograma e demonstrou o Histograma
plt.hist(img.ravel(), 256, (0,256))
plt.show()

Trazendo a vista, a mostra de pixels na imagem em questão.
