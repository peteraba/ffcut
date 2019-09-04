# ffcut
Simple wrapper around ffmpeg for easier cutting

    ffcut: simple wrapper around ffmpeg to make it easy to cut movies
    ---
    usage 1: ffcut inputFile length [startingPoint] [countPrefix]
    usage 2: ffcut inputFile startingPoint endingPoint [countPrefix]
    ---
    inputFile: relative or absolute path of the file to cut
    length: length as number of seconds (no default)
    startingPoint: time of first frame to include. Time expected (00:00:00.0 by default)
    endingPoint: time of first frame not to include. Time format expected (no default)
    countPrefix: expression to use before the count part of the output. ("cut" by default)
