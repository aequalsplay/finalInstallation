# finalInstallation
Code for submission to MSI340

Split across two applications:

  - Processing
  - SuperCollier
  
Processing sketch uses Boids to send OSC data to SuperCollider where various audio events are triggered.

Based on an evolutionary algorithm, Boids send attribtues to SuperCollider based on size, position, and health. 

SuperCollider uses this data to set paramaters such as pitch and filter cutoff frequency, panning, and triggereing/stopping sound events.

Visuals based on code by Daniel Shiffman ( The Nature of Code - https://natureofcode.com )




