## Steps to setup colab notebook hosted on remote GCP runtime

1. Install google-sdk on your local machine, if not already: https://cloud.google.com/sdk/docs/install#linux
2. Run `gcloud init` in a terminal window and follow the steps to authenticate your login
3. Connect to the remote GCP instance in port-forwarding mode - 

>`gcloud compute ssh xcsr-workshop --zone=us-central1-a -- -L 8081:localhost:8081`

4. Open the colab notebook in your browser (e.g. https://colab.research.google.com/github/usc-sail/ccmi-explorecsr/blob/main/workshop-1/xcsr_audio.ipynb)
5. Connect to local runtime and enter in the token link provided by your mentor (e.g. `http://localhost:8081/?token=0d3fdf1a5656aa400800ff8a33b9f40ade91ecd2b2718ff2`)\

<img src="/images/colab-runtime.gif">
