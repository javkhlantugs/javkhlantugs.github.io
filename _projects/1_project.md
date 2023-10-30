---
layout: page
title: Attention Visualizer
description: with Tensorflow and huggingface's transformers library.
img: assets/img/Attention_Layer1_Head3.png
importance: 1
category: fun
related_publications:
---

<div class="row mb-3">
    <div class="column">
        <a class="btn btn-outline-light" href="https://attention-visualizer-ee7107a5c006.herokuapp.com/">Site</a>
        <a class="btn btn-outline-info" href="https://github.com/javkhlantugs/attention_visualizer/blob/main/mask.py">Code</a>
    </div>
</div>

One way to create language models is to build a Masked Language Model, where a language model is trained to predict a “masked” word that is missing from a sequence of text. BERT is a transformer-based language model developed by Google, and it was trained with this approach: the language model was trained to predict a masked word based on the surrounding context words.

BERT uses a transformer architecture and therefore uses an attention mechanism for understanding language. In the base BERT model, the transformer uses 12 layers, where each layer has 12 self-attention heads, for a total of 144 self-attention heads.

I've built a simple program that takes a sentence with a word missing as an input and outputs 3 sentences with predictions of the hidden word. Also, it will generate diagrams for all of the 144 attention heads.

    ---
    Input sentence: 
     A person who never made a ______ never tried anything new.

    Predicted sentences:
    1. A person who never made a mistake never tried anything new.
    2. A person who never made a living never tried anything new.
    3. A person who never made a move never tried anything new.
    ---
<div class="row">
    <div class="col">
        <div class="card">
            <div class="card-header">
                Layer 1
            </div>
            <div class="card-body">
                <div class="container">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 1</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head1.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 2</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head2.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 3</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head3.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 4</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head4.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 5</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head5.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 6</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head6.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 7</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head7.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 8</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head8.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 9</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head9.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 10</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head10.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                                        <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 11</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head11.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card">
                            <h5 class="card-header">Head 12</h5>
                            <div class="card-body">
                                  {% include figure.html path="assets/img/Attention_Layer1_Head12.png" title="example image" class="img-fluid rounded z-depth-1" %}
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            </div>
        </div>
    </div>
</div>