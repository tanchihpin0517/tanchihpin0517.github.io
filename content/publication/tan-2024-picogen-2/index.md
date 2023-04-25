---
title: 'PiCoGen2: Piano cover generation with transfer learning approach and weakly
  aligned data'
authors:
- admin
- Hsin Ai
- Yi-Hsin Chang
- Shuen-Huei Guan
- Yi-Hsuan Yang
date: '2024-11-01'
publishDate: '2024-08-07T11:40:40.356223Z'
publication_types:
- paper-conference
publication: '*Proc. International Society for Music Information Retrieval Conference (ISMIR)*'
abstract: Piano cover generation aims to create a piano cover from a pop song. Existing approaches mainly employ supervised learning and the training demands strongly-aligned and paired song-to-piano data, which is built by remapping piano notes to song audio. This would, however, result in the loss of piano information and accordingly cause inconsistencies between the original and remapped piano versions. To overcome this limitation, we propose a transfer learning approach that pre-trains our model on piano-only data and fine-tunes it on weakly-aligned paired data constructed without note remapping. During pre-training, to guide the model to learn piano composition concepts instead of merely transcribing audio, we use an existing lead sheet transcription model as the encoder to extract high-level features from the piano recordings. The pre-trained model is then fine-tuned on the paired song-piano data to transfer the learned composition knowledge to the pop song domain. Our evaluation shows that this training strategy enables our model, named PiCoGen2, to attain high-quality results, outperforming baselines on both objective and subjective metrics across five pop genres.

featured: true

links:
- name: Website
  url: https://tanchihpin0517.github.io/PiCoGen/picogen2.html
url_pdf: https://arxiv.org/abs/2408.01551
url_code: 'https://github.com/tanchihpin0517/PiCoGen/tree/v2'
url_video: 'https://www.youtube.com/watch?v=bnu2L29c0nM'
---
