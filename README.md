# vibes
Vibes is a song popularity predictor. This is a personal side project made with a few friends.

The predictor takes in an MP3 file as input, analyze the file with librosa, trained it against features (energy, spectral energy,etc.) of 100 other Billboard 100 songs using sklearn with xgboost, and output a popularity score (one of the key features queried from Spotify's API).
