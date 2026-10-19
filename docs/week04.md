In week 4 I stopped using Gaussian fitting to get the loop widths and instead used Scipy's find_peaks width estimates, which finds the points on either side of each detected peak where the intensity reaches half the peak's prominence above the local baseline. 

I ran this width calculation over many small slices in one frame and got 46 measurements to create my first histogram. Later on in the week I changed this and took three longer slices instead, giving a better histogram.

I spent a good bit of time reading and taking notes on the paper Hayes et al 2026 "Fine-scale flare structures and their energetic implications from short-exposure extreme-ultraviolet imaging". I was already familiar with most the information on solar flares that I have needed so far for this project, but spending time reading the paper made me feel more confident in that knowledge. This reading shifted my focus to kernel width and separation measurements.

I also made GIFs of the short- and regular-exposure frame evolution, so that I could better understand which frames to look at for my kernel measurements next week.

By the end of the week, I had changed my slicing to take three long cuts across the arcade (still working with only 1 frame) and obtained 48 regular-exposure peaks. 

