# A Survey on Neural Audio Codec

A preliminary survey on neural audio codec.

* (2023/11) **Generative De-Quantization for Neural Speech Codec via Latent Diffusion**

    [[paper](https://arxiv.org/abs/2311.08330)] [[demo](https://saige.sice.indiana.edu/research-projects/LaDiffCodec/)]
    [[code](https://github.com/haiciyang/LaDiffCodec)] [Submitted to ICASSP 2024]

* (2023/09) **FunCodec: A Fundamental, Reproducible and Integrable Open-source Toolkit for Neural Speech Codec**

    [[paper](https://arxiv.org/abs/2309.07405)] [[demo](https://text-guided-vc.github.io/asru2023_demo/)]
    [[code](https://github.com/alibaba-damo-academy/FunCodec)] [Submitted to ICASSP 2024]

* (2023/09) **RepCodec: A Speech Representation Codec for Speech Tokenization**

    [[paper](https://arxiv.org/abs/2309.00169)]
    [[code](https://github.com/mct10/RepCodec)]


* (2023/08) **SpeechTokenizer: Unified Speech Tokenizer for Speech Large Language Models**

    [[paper](https://arxiv.org/abs/2308.16692)] [[demo](https://0nutation.github.io/SpeechTokenizer.github.io/)]
    [[code](https://github.com/ZhangXInFD/SpeechTokenizer/)]
    [disentangle semantic token]

* (2023/06) **DAC: High-Fidelity Audio Compression with Improved RVQGAN**

    [[paper](https://arxiv.org/abs/2306.06546)] [[demo](https://descript.notion.site/Descript-Audio-Codec-11389fce0ce2419891d6591a68f814d5)]
    [[code](https://github.com/descriptinc/descript-audio-codec)] [NeurIPS 2023]

* (2023/05) **AudioDec: An Open-source Streaming High-fidelity Neural Audio Codec**

    [[paper](https://arxiv.org/abs/2305.16608)] [[demo](https://bigpon.github.io/AudioDec_demo/)]
    [[code](https://github.com/facebookresearch/AudioDec)] [ICASSP 2023]

* (2023/05) **HiFi-Codec: Group-residual Vector quantization for High Fidelity Audio Codec**

    [[paper](https://arxiv.org/abs/2305.02765)]
    [[code](https://github.com/yangdongchao/AcademiCodec)]

* (2022/10) **High Fidelity Neural Audio Compression**

    [[paper](https://arxiv.org/abs/2210.13438)] [[demo](https://ai.honu.io/papers/encodec/samples.html)]
    [[code](https://github.com/facebookresearch/encodec)]

* (2021/07) **SoundStream: An End-to-End Neural Audio Codec**

    [[paper](https://arxiv.org/abs/2107.03312)] [[demo](https://google-research.github.io/seanet/soundstream/examples/)]


# Evaluation
You can refer to the analyses in AudioDecBenchmark [[Github](https://github.com/voidful/AudioDecBenchmark)], which include evaluations of different neural codecs in the below aspects:
* Reconstruction Quality
* Speech Synthesis
* Speech Comprehension
* Deconstruction of various elements within speech, for example, the inforamtion of speakers, timbre, prosody, etc.