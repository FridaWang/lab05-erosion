# lab05-Erosion
Shader toy link: https://www.shadertoy.com/view/DdfGW7

- 0s:
<img width="430" alt="lab05-1" src="https://user-images.githubusercontent.com/33616958/196788849-fb3e99ad-a25b-47de-9e76-ae4541c35d3e.png">

- 30s:
<img width="430" alt="lab05-2" src="https://user-images.githubusercontent.com/33616958/196788855-b92c30ab-c404-4dd8-96f2-58123ade2e31.png">

## 1. Code-In-The-Blanks
Imagine a terrain height field, where white is the highest height and black is the lowest height. We'll stick to 2d for ease of visualization. We can generate an interesting organic-looking height field like this with noise:

<img width="478" alt="Screenshot 2022-10-18 214809" src="https://user-images.githubusercontent.com/1758825/196586616-18a3a244-22d3-4563-afd0-b4c1627bb42d.png">

Not bad, but not good either. We can make it look MORE like terrain by mimicking the effects of erosion. If you imagine material sliding down steep slopes to re-distribute some of the height, it might look more like this:

<img width="476" alt="Screenshot 2022-10-18 214636" src="https://user-images.githubusercontent.com/1758825/196586668-aa5aef65-d9fc-471a-8fb2-2580660f2b0b.png">

Fork [this base code](https://www.shadertoy.com/view/cdl3W4) and replicate (to the best of your ability) this erosion effect. More detailed instructions inside! 

## 2. Beautiful colors
Add some coloring to give the terrain some personality.

## Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solutions
- Make sure your shadertoy is set to UNLISTED or PUBLIC (so we can see them!)
