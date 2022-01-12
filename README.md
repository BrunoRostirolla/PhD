# PhD - Photocapacitance Modelling

  The last chapter of my PhD thesis was aimed at improving a model that describes how the capacitance-voltage (CV) measurement, in an organic-based MIS (Metal-Insulator-Semiconductor) device, would change when exposed to light.
  
  With common semiconductors, like Si, the behaviour of the CV is well understood. The device can be driven to accumulation, depletion, deep depletion and inversion when the voltage across the metal electrodes change. Superimposed to the DC voltage there is also a small AC signal, where its frequency plays an important role. But let me explain better.
  
  
![image](https://user-images.githubusercontent.com/49575048/149145325-a1606339-3dac-4147-8dc4-4e965073934d.png)
  
  This scheme represents the device that we actually made. Think of it as two materials (the insulator and the semiconductor, in this case P3HT, an organic semiconductor) sandwiched between two metal plates. 
  
  Depending on the applied voltage at the metal electrodes, electric charges can move inside the semiconductor and change the capacitance of the whole device because, simply put, semiconductors are materials that can display, depending on how they are manipulated, both insulator and metalic properties.
  
  During the accumulation regime, the electric charges inside the semiconductor are accumulated (duh) at the semiconductor/insulator interface, making the semiconductor act as an extension of the top metalic electrode. In this case, the measured capacitance is only the insulator one. From this measurement, we can infer the thickness of the insulator layer for example. As we change the applied voltage, charges are pushed away from the interface and a new "insulator" layer is formed inside de the semicondutor, this layer is called depletion layer. Now, the measured capacitance is the series sum of the insulator capacitance and the depletion region capacitance. 
  
  Anyone familiar with electric components would already figure out that the measured capacitance will also depend on the thickness of the depletion layer. The thing is, some of the charges that the electric field pushed away from the insulator/semiconductor interface actually remained trapped in the interface. The presence of these charges change the CV profile of the device. 
  
  There is another element to this as well. When we measure the CV with the device exposed to light that the semiconductor can absorb, the CV profile also changes. 
  
  How all these elements contribute to the capacitance profile of the device? 
