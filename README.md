# QUIC-vs-HTTPS-performance
This is a small assignment that compares QUIC (and HTTP) vs the HTTPS stack (TCP+TLS+HTTP) in a rather unorthodox manor. It does not make use of the QUIC client and server, but instead attempts to use live websites (e.g youtube.com) that has QUIC and HTTPS enabled.

This examination uses the Lighthouse tool and the Google Devloper Tool in order to take measurements, each measurement has been measured ten times, and an average calculation is used in order to reduce the impact of singular (strange) metrics. You can read more about this in papers, that might be linked here after they have been approved. :)

## Here are some images of the result
<img src="images/devtools_average.png" width="50%" height="50%">
<img src="images/devtools_percentage.png" width="50%" height="50%">
<img src="images/lighthouse_average.png" width="50%" height="50%">
<img src="images/lighthouse_percentage.png" width="50%" height="50%">
