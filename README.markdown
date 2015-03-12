# DTMF dialer

Dial a telephone number on your POTS phone.

**Why?** because the buttons of my telephone are broken.

## Content

 - `dtmf-dialer.bash`, the main implementation;

 - `dtmf-dialer.bash`, an implementation in bash;

 - `dtmf-dialer-cinform`, confirmation dialog.

## User documentation

### Basic usage

1. Adjust the volume of your computer;

2. Take your (POTS) telephone handset and place its microphone near
   your computer speaker/headphone;

3. Run the program:

   ~~~sh
   dtmf-dialer 33-456789
   ~~~

4. Wait and speak.

You need to ajust the volume of your computer speaker and the relative
position of your telephone microphone in order to have as suitable
reception of the DTMF signal.

* If they are too far apart or if the volume is too high, the signal will
  be too weak;

* If they are too near or if the volume is too low, you will have
  distortion.

## Roadmap

* argument processing;

* support for country prefixes (and exit prefix);

* real [`tel:` URI](http://www.ietf.org/rfc/rfc3966.txt) handling
