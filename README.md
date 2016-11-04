# VaisalaHMP60
Serial DAQ for a Vaisala HMP60 relative humidity probe

# Instructions
1.  Connect the Vaisala USB cable but DO NOT connect the probe to the cable.
2.  Open PuTTY and select the correct COM port.  The default values are:
            - Baud: 19200
            - Data bits: 8
            - Stop bits: 1
            - Parity: None
            - Flow Control: None
3.  Click "Open".
4.  While holding down the "Enter" key, connect the probe to the cable.  This initializes the probe in RS-485 mode.
5.  Close the PuTTY window and confirm closing the session.
6.  Begin collecting data with LabVIEW.
