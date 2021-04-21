# 20210422

2021-04-20-002 {
fractal:
  title="2021-04-20-002" width=1593 height=912 layers=1
  credits="Rupert Russell;4/21/2021" antialiasing=yes
layer:
  caption="Background" opacity=100
mapping:
  center=-0.6745898607297849538417/-0.4652354752255640874175
  magn=2.1559107E11
formula:
  maxiter=100000 filename="Standard.ufm" entry="Mandelbrot"
  p_start=0/0 p_power=2/0 p_bailout=128
inside:
  transfer=none
outside:
  density=16 transfer=log filename="Standard.ucl" entry="Smooth"
  p_power=2/0 p_bailout=128.0
gradient:
  smooth=yes rotation=1 index=0 color=6555392 index=64 color=13331232
  index=249 color=7536640 index=257 color=43775 index=343 color=512
opacity:
  smooth=no index=0 opacity=255
}
