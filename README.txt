This was implemented in MATLAB R2015a.

'my_dtmf.m' has implemented a dual-tone-multi-frequency generator. It takes in tone_time in seconds, quiet_time in seconds, sampling_frequency in Hz, and dial_vals an array of any length of digits 0-9 used to generate the tones. 
It outputs dial_sig, the array representing the DTMF tone at the given frequency.

'detectionScript.m' is a script that does the detection of generated signals.

'run_script.m' generates a test signal, adds noise, and detects it using the the files above. You can change dial_vals to see other results.