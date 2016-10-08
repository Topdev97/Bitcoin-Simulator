# Bitcoin-Simulatior
Bitcoin Simulator is built on ns3, the popular discrete-event simulator. We also made use of rapidjson to facilitate the communication process among the nodes. The purpose of this project is to study how consensus parameteres, network characteristics and protocol modifications affect the scalability, security and efficiency of Proof of Work powered blockchains.

Our goal is to make the simulator as realistic as possible. So, we collected real network statistics and incorporated them in the simulator. Specifically, we crawled popular explorers, like blockchain.info to estimate the block generation and block size distribution, and used the bitcoin crawler to find out the average number of nodes in the network and their geographic distribution. Futhermore, we used the data provided by coinscope regarding the connectivity of nodes.

We provide you with a detailed installation guide (http://arthurgervais.github.io/Bitcoin-Simulation/Installation.html), containing a video tutorial (http://arthurgervais.github.io/Bitcoin-Simulation/Installation.html), to help you get started. You can also check our experimental results (http://arthurgervais.github.io/Bitcoin-Simulation/results.html) and our code. Feel free to contact us or any questions you may have.
