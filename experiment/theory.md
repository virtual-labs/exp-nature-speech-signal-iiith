1. Obtaining speech signal

    Load speech signals for heed, head, hod using the provided utility.

2. To obtain average pitch period

   - Display the recorded speech waveform.
     <center><img src="images/img11.png"> <br></p> </center>

    $/i/$
    Figure 1: Speech waveform for the utterance "heed-head-hod"



   - Select the vowel segment. A segment of the vowel /i/ is shown in the Figure 2.
<center><img src="images/img12.png"  > <br></p> </center>
    $/i/$
    Figure 2: A part of the vowel /a/ in the speech segment of 'hod'

   - The quasi-periodic nature of prominent peaks shown in Figure 2 is due to the regular vibration of the vocal folds.

   - Pitch period (\(T_{0}\)) is measured as the interval between any two successive prominent peaks.

   - The speech signal between two successive prominent peaks corresponds to one pitch cycle.

   - Note the time (in msec) of the pitch period for three or four pitch cycles (say) and measure the average pitch period, preferably in the steady portion of the speech signal as illustrated in Figure 2.

   - As pitch period is not constant over the entire vowel segment, make four or five pitch period measurements.

   - Mean of these values gives average pitch period (\(T_{0}\)) and hence fundamental frequency (\(F_{0} = \frac{1}{T_{0}}\)).

   - Average pitch period can also be obtained from the autocorrelation sequence of corresponding speech segments. Measure the distance between the peak at zero and the next prominent peak in either the positive or negative delays of the obtained autocorrelation sequence.


3. To obtain formant frequencies

    - Select voiced segment of the recorded speech segment using the provided utility.

    Figure 3 shows the LP spectrum obtained using Linear prediction analysis of voiced region of speech segment /hod/ with LP order set to 10.
<center><img src="images/img14.png"  > <br></p> </center>
    $/i/$
    Figure 3: LPC spectrum of a short segment of vowel /a/ in the utterance of 'hod'. The spectrum is obtained using 10th order LP analysis. As shown in the figure, the peaks of the LP spectrum represent the formant frequencies.

   - The peaks of the LP spectrum shown in Figure 3 represent the resonant frequencies (also called Formants) of the vocal tract.

   - Repeat the above steps for recorded speech of all vowels.

   - Repeat the above procedure for recorded speech of different speakers.


