***********************************************
LabVIEW NeuroSky 1.0.0.0 Driver and Application
***********************************************

Implemented a LabVIEW Project with a RN-4X bluetooth module and
the Neurosky Mindwave Mobile.

.\ Neurosky LabVIEW.lvprj - Project with the application and VIs
  .\ Neurosky.vi       - Main Application
  .\ Neurosky.lvlib    - Library
    .\Neurosky\ MindwaveAUTO.vi - Gets a RAW Wave sample and a BigPacket
    .\Neurosky\ MindwaveClose.vi - Close the COMM Port
    .\Neurosky\ MindwaveCmpChksum.vi - Compares the calculated with the real checksum
    .\Neurosky\ MindwaveCompute2Bytes.vi - Calcs the "signed short" raw wave value
    .\Neurosky\ MindwaveCompute3Bytes.vi - Calcs the "unsigned long" braiwave alpha, delta, gamma... waves.
    .\Neurosky\ MindwaveGetPAYLOAD.vi    - Gets the payload of the frame
    .\Neurosky\ MindwaveGetPLENGTH.vi    - Gets the length of the payload
    .\Neurosky\ MindwaveInit.vi          - Open the virtual serial port
    .\Neurosky\ MindwaveParseData.vi     - Data parser for bigpacket and tiny packet
    .\Neurosky\ MindwavePrecise.vi       - Could select by a control input: the stream, the raw wave or the big packet
    .\Neurosky\ MindwaveReadByte.vi      - Reads one byte of the serial port
    .\Neurosky\ MindwaveStream.vi        - Gets all data (raw, brainwave, meditation, etc.)
 
