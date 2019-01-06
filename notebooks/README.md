## Implementation Details

The notebooks in this folder implement estimation of Mutual Information using different lower-bound objective functions described in the papers mentioned in the repository.
Some of these techniques include the Mutual Information Neural Estimation (MINE), Nguyen Wainwright Jordan (NWJ) loss, Jensen Shannon Divergence (JS) loss, Noise Contrastive Estimation(NCE) loss, etc. The neural network is trained using PyTorch and the calculated MI estimates are plotted against the MI obtained using the traditional method (the basic definition of MI).
