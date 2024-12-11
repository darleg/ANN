
Activation functions are key players in artificial neural networks (ANNs). 
They determine whether a neuron should be activated or not by transforming 
the weighted sum of inputs into an output signal for the next layer. Let's 
break down some of the most commonly used activation functions:
1. Sigmoid Function (Logistic Function):
* Formula: <math xmlns="http://www.w3.org/1998/Math/MathML">
  <mstyle displaystyle="true">
    <mi>&#x3C3;</mi>
    <mrow>
      <mo>(</mo>
      <mi>x</mi>
      <mo>)</mo>
    </mrow>
    <mo>=</mo>
    <mfrac>
      <mn>1</mn>
      <mrow>
        <mn>1</mn>
        <mo>+</mo>
        <msup>
          <mi>e</mi>
          <mrow>
            <mo>-</mo>
            <mi>x</mi>
          </mrow>
        </msup>
      </mrow>
    </mfrac>
  </mstyle>
</math>
