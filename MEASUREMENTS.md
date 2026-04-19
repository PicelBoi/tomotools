# Measurements

Here are the exact mesasurements and what was used to take them.

## Voice

### Pitch

- Depth, Speed, and Delivery set to 25 (middle)
- Music and Sound volumes were set to 0
- [Online Mic Test's Pitch Detector](https://www.onlinemictest.com/tuners/pitch-detector/) on an iPhone 13 mini was used to get pitches.

| Speed Value | Hz Measurement |
| ----------- | -------------- |
| 0           | 24.5hz         |
| 1           | 27.5hz         |
| 2           | 27.8hz         |
| 3           | 29.6hz         |
| 4           | 31.6hz         |
| 5           | 33.9hz         |
| 6           | 36.3hz         |
| 7           | 38.2hz         |
| 8           | 40.7hz         |
| 9           | 43.4hz         |
| 10          | 46.2hz         |
| 11          | 49.3hz         |
| 12          | 52.6hz         |
| 13          | 56.0hz         |
| 14          | 59.9hz         |
| 15          | 64.3hz         |
| 16          | 68.3hz         |
| 17          | 72.2hz         |
| 18          | 76.9hz         |
| 19          | 82.1hz         |
| 20          | 87.0hz         |
| 21          | 93.1hz         |
| 22          | 99.1hz         |
| 23          | 105.5hz        |
| 24          | 112.8hz        |
| 25          | 120.0hz        |
| 26          | 127.9hz        |
| 27          | 136.2hz        |
| 28          | 145.5hz        |
| 29          | 154.9hz        |
| 30          | 165.4hz        |
| 31          | 175.8hz        |
| 32          | 187.9hz        |
| 33          | 200.3hz        |
| 34          | 212.8hz        |
| 35          | 227.1hz        |
| 36          | 247.1hz        |
| 37          | 257.6hz        |
| 38          | 275.8hz        |
| 39          | 292.3hz        |
| 40          | 311.8hz        |
| 41          | 332.7hz        |
| 42          | 353.6hz        |
| 43          | 377.6hz        |
| 44          | 402.3hz        |
| 45          | 427.6hz        |
| 46          | 456.6hz        |
| 47          | 487.5hz        |
| 48          | 517.4hz        |
| 49          | 551.8hz        |
| 50          | 588.0hz        |

### Speed

- Passage: My name is Evil. It's nice to meet you. Today is April 18th, 2026. So, how does this voice sound?
- Equation for calculating wpm is $(60/x)y$, with x being duration and y being the amount of words

| Pitch Value | Duration | WPM          |
| ----------- | -------- | ------------ |
| 0           | 13s      | 92.308 wpm   |
| 12          | 11s      | 109.0909 wpm |
| 25          | 10s      | 120 wpm      |
| 38          | 9s       | 133.333 wpm  |
| 50          | 7s       | 171.429 wpm  |

### Delivery

- Music and Sound volumes were set to 0
- Each side of the delivery slider do the same, but left is low to high while right is high to low.
- Each side is 25 values long.
- Base pitch is 25 (120hz)
- Delivery Variance Percent is calculated by $x/y$, with x being the Highest Hz Measurement and y being the base pitch.

| Delivery Side Value | Highest Hz Measurement | Variance Percent |
| ------------------- | ---------------------- | ---------------- |
| 0                   | 120hz                  | 100%             |
| 6                   | 150.3hz                | 125.25%          |
| 12                  | 248.6hz                | 207.16%          |
| 18                  | 295.5hz                | 246.25%          |
| 25                  | 360.1hz                | 300.08%          |
