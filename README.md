This class can be used to manipulate MP3 audio files.

It can open an MP3 audio file and parse it to retrieve information about the data in its frames.

The class can also change and delete frames of the MP3 audio file and save the results to a separate file.

# USAGE

    require_once './class.mp3.php';
    $mp3 = new mp3;
    $mp3->cut_mp3('input.mp3', 'output.mp3', 0, -1, 'frame', false);
    
`the 'frame' can be substituted with 'second' or 'percent' to base the cut on a time-frame or percentages of the original audio.`

