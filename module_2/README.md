Image generated artificial engine sound generator: Image of supercar (Aria Dio) converted to Engine sounds (Work in Progress)

## Workflow

1.  [Photosounder](https://photosounder.com/download.php) is used to convert [an image of Aria Dio](aria_dio_input_image.png), into wave sound format!
2.  Audacity is used to refine result from above, i.e. noise reduction & artificial stretching.
3.  [An open-source car engine sound simulator](https://github.com/buntine/CarEngines) is then used to simulate acceleration/deceleration sounds, given sound from above

## Screenshot

![image](screenshot__.png)


## Video

https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module_2/video_.mp4

## Future work

Instead of the current engine sound source, namely photosounder output (non-deep learning method) from image, the goal is to convert video of aria dio into sound, using a deep learning method, like [regnet](https://github.com/PeihaoChen/regnet#readme).
