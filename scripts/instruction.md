python3 download_audio.py \
    --episodes SEP-28k_episodes.csv \
    --wavs ../audio

python3 extract_clips.py \
    --labels SEP-28k_labels.csv \
    --wavs ../audio \
    --clips ../clips \
    --progress