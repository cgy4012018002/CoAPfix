# CoAPfix
The Constrained Application Protocol (CoAP) is a lightweight communication protocol used for enabling Internet communication on resource-constrained network devices. It is widely applied in scenarios such as the Internet of Things (IoT) and sensor networks. In this paper, we analyze the security of the CoAP by constructing a modular symbolic model and use the Tamarin prover to verify the security requirements that CoAP should meet. In the analysis, it was found that there is an issue of insufficient anonymity. Due to this anonymity problem, there may be a risk of mali-cious adversaries maliciously monitoring the location information of device users, leading to the exposure of location privacy. In response to this critical flaw, this paper proposes improvements to the CoAP, introducing CoAP+, aimed at enhancing the protocol's anonymity and thereby im-proving its security in IoT communication. Overall, this paper not only provides an effective method for analyzing the security of the CoAP used by IoT devices but also offers valuable insights and strategies for enhancing its security performance.
