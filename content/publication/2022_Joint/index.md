---
title: "Joint Device Selection and Power Control for Wireless Federated Learning"
date: 2022-08-01
publishDate: 2022-08-01
authors: ["Wei Guo", "Ran Li", "Chuan Huang", "Xiaoqi Qin", "Kaiming Shen", "Wei Zhang"]
publication_types: ["2"]
abstract: "This paper studies the joint device selection and power control scheme for wireless federated learning (FL), considering both the downlink and uplink communications between the parameter server (PS) and the terminal devices. In each round of model training, the PS first broadcasts the global model to the terminal devices in an analog fashion, and then the terminal devices perform local training and upload the updated model parameters to the PS via over-the-air computation (AirComp). First, we propose an AirComp-based adaptive reweighing scheme for the aggregation of local updated models, where the model aggregation weights are directly determined by the uplink transmit power values of the selected devices and which enables the joint learning and communication optimization simply by the device selection and power control. Furthermore, we provide a convergence analysis for the proposed wireless FL algorithm and the upper bound on the expected optimality gap between the expected and optimal global loss values is derived. With instantaneous channel state information (CSI), we formulate the optimality gap minimization problems under both the individual and sum uplink transmit power constraints, respectively, which are shown to be solved by the semidefinite programming (SDR) technique. Numerical results reveal that our proposed wireless FL algorithm achieves close to the best performance by using the ideal FedAvg scheme with error-free model exchange and full device participation."
featured: false
publication: "*IEEE Journal on Selected Areas in Communications*"
---
