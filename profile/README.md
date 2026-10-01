<p align="center">
  <img src="assets/banner.png" alt="alice-noa-chan" width="100%">
</p><p align="center">
  <strong>Models and experiments exploring architectures, training methods, and unusual ideas.</strong>
</p><p align="center">
  A personal collection of machine learning experiments.
</p>

---

I build models and experimental systems to try different ideas in model architecture, training, inference, and evaluation.

Projects here range from small language models and translation systems to new encoder architectures, structured decision models, and experiments that use existing models in unusual ways.

Not every experiment is intended to become a production model. Some exist simply to answer a question, compare an idea against a baseline, or find out why something does not work.

Featured projects

<table>
<tr>
<td width="50%" valign="top">
<h3>Hana</h3><p>
A decoder-only language-model research pipeline built around reproducible training and experimentation.
</p><p>
Includes tokenizer training, pretraining, supervised fine-tuning, preference optimization, evaluation, checkpointing, inference, quantization, and architecture experiments.
</p><p>
<a href="https://github.com/alice-noa-chan/hana"><strong>Repository →</strong></a>
</p>
</td><td width="50%" valign="top">
<h3>Haru</h3><p>
A family of compact Korean language models for story continuation.
</p><p>
Haru explores small-model architecture, teacher-student training, distillation, parameter sharing, attention variants, and different approaches to obtaining useful behavior under limited parameter budgets.
</p><p>
<a href="https://github.com/alice-noa-chan/haru"><strong>Repository →</strong></a>
</p>
</td>
</tr><tr>
<td width="50%" valign="top">
<h3>Ayaka</h3><p>
Structured decision models that return calibrated probabilities over runtime candidate sets.
</p><p>
Ayaka experiments with specialized decision heads, shared state encoding, calibration, efficient single-pass decisions, and optional reasoning for difficult quantitative tasks.
</p><p>
<a href="https://github.com/alice-noa-chan/ayaka"><strong>Repository →</strong></a>
</p>
</td><td width="50%" valign="top">
<h3>Siho / BLADE</h3><p>
An encoder architecture designed to operate directly on UTF-8 bytes.
</p><p>
BLADE explores adaptive byte patching, bidirectional local processing, recurrent latent computation, entropy-guided allocation, and optional residual vector quantization without a conventional subword tokenizer.
</p><p>
<a href="https://github.com/alice-noa-chan/siho"><strong>Repository →</strong></a>
</p>
</td>
</tr><tr>
<td width="50%" valign="top">
<h3>kobato</h3><p>
An experiment in adapting a Korean encoder-decoder model for Japanese-to-Korean translation.
</p><p>
The project covers corpus curation, tokenizer adaptation, large-corpus training, evaluation, checkpoint recovery, and practical translation inference.
</p><p>
<a href="https://github.com/alice-noa-chan/kobato"><strong>Repository →</strong></a>
</p>
</td><td width="50%" valign="top">
<h3>DELECTRA</h3><p>
An experiment asking whether ELECTRA can be made to behave like a decoder without training new weights.
</p><p>
Its generator proposes tokens, its discriminator evaluates them, and different scoring strategies are tested to determine how far the original pretrained model can be pushed.
</p><p>
<a href="https://github.com/alice-noa-chan/DELECTRA"><strong>Repository →</strong></a>
</p>
</td>
</tr>
</table>What I experiment with

# Architectures
Decoder models, byte-level encoders, recurrent computation, parameter sharing, attention variants, adaptive representations, and unusual combinations of existing components.

# Training
Pretraining, supervised fine-tuning, distillation, preference optimization, parameter-efficient methods, data curation, and controlled architecture comparisons.

# Inference
Structured prediction, probability calibration, candidate scoring, reasoning routes, caching, quantization, and generation experiments.

# Small models
Many projects deliberately use relatively small models so architectural and training changes can be tested repeatedly and understood more directly.

# Korean and Japanese NLP
Language modeling, story continuation, translation, classification, tokenization, and multilingual experiments.

# Evaluation
Benchmarks, ablations, controlled comparisons, calibration measurements, failure analysis, and experiments designed to distinguish real improvements from accidental ones.

# How I work

## Build the idea

Many projects begin with a simple question:

## «What happens if I try this?»

Instead of assuming an architecture or technique should work, I prefer implementing it and measuring the result.

## Compare it

Whenever possible, a new technique is tested against a baseline or an alternative configuration.

A more complicated method is not automatically a better one.

## Keep negative results

Experiments that fail can still be useful.

Several repositories preserve approaches that looked promising but did not survive further testing, along with the measurements that led to rejecting them.

## Document the details

I try to keep architecture choices, training configurations, evaluation procedures, limitations, and implementation details visible rather than publishing only a final checkpoint.

## More experiments

There are also smaller projects involving classification, routing, navigation, games, text processing, and other machine learning problems.

Some projects publish trained model weights, while others are code, architecture, or experimental studies only. When weights are available, the corresponding repository links to them.

<br><p align="center">
  <strong>Build an idea. Test it. Keep what was learned.</strong>
</p>
