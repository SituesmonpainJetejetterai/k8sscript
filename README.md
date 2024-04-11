# k8sscript

Spin up Kubernetes master and worker node for Red Hat Linux family

control plane+worker node

metrics

Cillium eBPF without kube-proxy as CNI

for k8s > 1.29

Tested with: 
Rocky 9
Alma 9
K8s 1.29.3
containerd 1.6.28
Calico
Cillium+eBPF

Use a user with sudo, edit the script and fill in:

$KSHOST with FQDN of node

$NODE with "controlplane" or "worker" (as examples) \
Note that using upper-case letters in the FQDN (i.e. akin to "ControlPlane" or "Worker") for the machine might not work; currently non-reproducible issue of `etcd` complaining against an FQDN with the aforementioned (upper-case) characters.

Recommend VMs with at least 4GB disk free at /var +4GB of RAM

For reapplying the script for the control plane(s), run kubeadm reset in all nodes.


## [![Repography logo](https://images.repography.com/logo.svg)](https://repography.com) / Recent activity [![Time period](https://images.repography.com/36666788/ruyrybeyro/k8sscript/recent-activity/EZJtwo3jB2EwKKnUEewLvL1dne-nTujKxziXYL-O0bU/tF14POcQca7kt6qHavYyeh4eHLBVJEoR_dLRGWThBcY_badge.svg)](https://repography.com)
[![Timeline graph](https://images.repography.com/36666788/ruyrybeyro/k8sscript/recent-activity/EZJtwo3jB2EwKKnUEewLvL1dne-nTujKxziXYL-O0bU/tF14POcQca7kt6qHavYyeh4eHLBVJEoR_dLRGWThBcY_timeline.svg)](https://github.com/ruyrybeyro/k8sscript/commits)
[![Trending topics](https://images.repography.com/36666788/ruyrybeyro/k8sscript/recent-activity/EZJtwo3jB2EwKKnUEewLvL1dne-nTujKxziXYL-O0bU/tF14POcQca7kt6qHavYyeh4eHLBVJEoR_dLRGWThBcY_words.svg)](https://github.com/ruyrybeyro/k8sscript/commits)
[![Top contributors](https://images.repography.com/36666788/ruyrybeyro/k8sscript/recent-activity/EZJtwo3jB2EwKKnUEewLvL1dne-nTujKxziXYL-O0bU/tF14POcQca7kt6qHavYyeh4eHLBVJEoR_dLRGWThBcY_users.svg)](https://github.com/ruyrybeyro/k8sscript/graphs/contributors)


