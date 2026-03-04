# Computational Musicology Portfolio - Mikayla van den Berg

My corpus consists of several recordings of Beethoven’s sonatas no.’s 8 (Pathétique), 14 (Moonlight) and 21 (Waldstein). 
These recordings span from the 60s to very recent ones from 2025.

## Cepstrogram

I have made a cepstrogram of a performance by Brendel of the 3rd movement of sonata no. 14. 

*Cepstrogram of Beethoven's Moonlight Sonata, 3rd movement. 
Performance by Brendel. Normalisation: Manhattan*

![](cepstrogram_moonlight_III_brendel.png)

As the name suggests, a piano sonata is played by one instrument, so not much variation is visible
on the cepstrogram. There are, however, some 'spikes' visible at around 250 second and near the end.
These are moments in the piece when the piano is not or barely audible. This way other background noises
are picked up and thus visible in the cepstrogram.

## Chromagram

I have also made a chromagram of a performance by Burchbinder of the first movement of sonata no. 8.

*Chromagram of Beethoven's Pathétique Sonata (No. 8), 1st movement. 
Perfomance by Buchbinder. Normalisation: Chebyshev*

![](chromagram_pathetique_I_buchbinder.png)

This piece is in c-minor and starts with the c-minor chord (C-E♭-G). Looking at the chromagram overall, it doesn’t become immediately clear that the piece is in c-minor. 
However, the beginning does have a high magnitude on the note C. The C also becomes more prominent at the end of the piece.
During the rest of the piece, the E♭ is also being emphasized a lot, especially around 150 seconds.
This is when the piece switches to the key e♭-minor (during the second subject). Shortly after it also modulates to E-major, hence the strong magnitude.

## Self-Similarity Matrices

Below are two Self-Similarity Matrices (SSM) of a performance by Brendel of the first movement of sonata no 14.
The first one is based on timbre and the second one on pitch. Note: the one based on timbre only consists of 100 seconds of the recording.
I have not had the time yet to get the full recording (it took forever to generate the plot).

*Self-similarity matrix based on timbre of Beethoven's Moonlight Sonata (No. 14), 3rd movement. 
Performance by Brendel. Normalisation: Euclidean. Distance: cosine.*

![](ssm_timbre_moonlight_III_brendel.png)

*Self-similarity matrix based on pitch of Beethoven's Moonlight Sonata (No. 14), 3rd movement. 
Performance by Brendel. Normalisation: Euclidean. Distance: cosine.*

![](ssm_pitch_moonlight_III_brendel.png)

As mentioned before, the only instrument in the piece is a piano. That is why the SSM based on pitch
looks unvarying (apart from the dark blue diagonal). There are, however, some yellow lines visible.

The SSM based on pitch looks much different. In comparison to the SSM based on timbre, there is a lot of variety in this one. 
This piece is in c♯-minor and in sonata form, which means that the exposition get's repeated. 
This happens at around a 100 seconds and a (faint) blue diagonal line is visible at this point in the SSM. 
The entirety of the exposition is visible as a block-like structure around 215 seconds (with a yellow outline). 
Here the second theme sounds in f♯-minor, which is different from the exposition where it was in g♯-minor.

There is not a block-like structure visible for the entirety of the development, which ends at around 265 seconds. 
At this point the recapitulation starts with the first subject remaining unaltered. The second subject is now in the tonic (instead of g♯-minor as in the exposition).

The overall SSM has a lot of block-like structures, but these are not easy to distinguish from each other and they cannot easily be linked to what is audible in the audio. 
The reason for this, is that piano sonatas in sonata form are build on themes and motives that get repeated but could also get slightly altered. 
Thus, there is a lot of homogeneity.