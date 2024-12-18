# RTEmotionRecognition

Abstract
The project seeks to design and implement a real-time emotion recognition system for music
using the ReSpeaker HAT microphone array. It will differentiate emotions into positive, negative,
and neutral from streamed audio by extracting features such as tempo, pitch, and lyrics. Libraries
such as LibROSA will assist in detecting emotion in the system. The results will help
demonstrate the viability of real-time streaming and classification with potential applications in
music therapy, entertainment systems, social media platforms, and interactive music experiences.

Introduction
Music is a universal medium that has existed throughout human history and, according to some
belief systems, predates humans. It generates strong emotional responses, and in recognizing
these responses in real-time, we can change our approach to musical interactions, enabling
personalized experiences such as feedback for live performances, creating dynamic playlists for
users, or even “Shazaming” songs when you hear them in public spaces.

The problem the project addresses is the need for a robust real-time solution to classify emotions
from streamed audio, especially for music. Ordinarily, emotion recognition systems focus on
transcribing speech or text for analysis; music requires a variety of extractions from tempo to
pitch to vocal to spectral analysis to predict the conveyed emotions more accurately. Capturing
and classifying these features in real-time with minimal latency is a technical challenge,
especially when working with continuous audio input, and it makes real-time audio significant as
it provides immediate insights and feedback.

Background
Emotion recognition in music is a growing research field within audio processing and machine
learning. Unlike speech emotion recognition, which focuses more on linguistics, music emotion
recognition relies on complex audio features, including speech, pitch, rhythm, tempo, and
spectral contrast. It has involved machine learning algorithms such as k-nearest Neighbors,
Support Vector Machines, and Neural Networks to predict emotional states based on extracted
features.

Real-time audio processing introduces more challenges than offline analysis. Capturing and analyzing live audio demands efficient feature extraction and classification pipelines to reduce
latency. Libraries and tools like LibROSA simplify feature extraction as they possess built-in
functions that calculate tempo, chroma, and spectral features, while PyAudio enables real-time
audio streaming from devices like ReSpeaker HAT, which is a microphone array add-on for
Raspberry Pi.

ReSpeaker HAT is vital to this project as it provides high-quality audio input with noise
suppression and beamforming features so that captured audio is clean and suitable for feature
extraction, even in noisy environments. By combining the hardware capabilities of Raspberry Pi
and ReSpeaker HAT with the software Python-based libraries for audio processing and machine
learning, this project encapsulates real-time audio and language processing concepts with both
theoretical and practical implementation.
