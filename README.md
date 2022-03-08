# DD_Debate_Analysis

Some statistics on the Dylan/Destiny vs Haz/Hinkel debate on the Ukraine-Russia conflict.

Got curious after Haz kept complaining he "*hadn't talked at all*" yet.


## How the data was gathered

I used Destiny's [video](https://www.youtube.com/watch?v=pqktQZT5W2w) on the debate as a basis and 
extracted every 6th frame from the debate (starting at 201 seconds into the video) as a full res image resulting in 
75,739 images (or 28GB of data).

I defined areas around each participants camera that would light up according to when they are using their mic: 

Yes, both the tiny indicator below and also the full indicator (data is kept separately).

Analyzed the average color value of the defined areas on each frame to recognize active mics for each participant.

Charts are generated from that data.

### What else
- The csv with the full generated colors (rgb) is included in the repo, the actual frames are not (due to size constraints).
- The jupyter notebook used to generate everything is included and should, with little to no work, be able to reproduce
the results provided one downloads the original video (and creates a `frames/` folder)
  
