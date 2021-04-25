Image generated artificial engine sound generator: Image of supercar (Aria Dio) converted to Engine sounds (Work in Progress)

1) Imagining Aria Dio as an electric supercar, I quickly put together this image based engine sound audio demo. Engine sounds are generated from a picture of Aria Dio.

2) Using mostly harmonic/sound based methods as starting points, some electric car manufacturers are experimenting with engine sounds for quiet evs, as this can help to help notify separate motorists of the operating conditions of the electric car. (Sample: https://www.hindawi.com/journals/sv/2018/5209207/)

3) Here I consider a reasonably novel/simple startng method, i.e. starting from an actual picture of my AriaDio supercar concept, and synthesizing engine sounds from there.


## Workflow

1.  [Photosounder](https://photosounder.com/download.php) is used to convert [an image of Aria Dio](aria_dio_input_image.png), into wave sound format!
2.  Audacity is used to refine result from above, i.e. noise reduction & artificial stretching.
3.  [An open-source car engine sound simulator](https://github.com/buntine/CarEngines) is then used to simulate acceleration/deceleration sounds, given sound from above

## Screenshot

![image](screenshot__.png)


## Video

https://youtu.be/KR1do0lP6Bw

## Future work

Instead of the current engine sound source, namely photosounder output (non-deep learning method) from image, the goal is to convert video of aria dio into sound, using a deep learning method, like [regnet](https://github.com/PeihaoChen/regnet#readme).
