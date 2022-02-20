
<p align="center">
<img src="static/ctfd-helm.png">
<h3>A Helm Chart for CTFd</h3>
</p>

### What is CTFd?
CTFd is a Capture The Flag framework focusing on ease of use and customizability. It comes with everything you need to run a CTF and it's easy to customize with plugins and themes.

### Let's get started
##### Prerequisites: oc client, helm, a k8s/OpenShift cluster

To get started, simply adjust the values in the `values.yaml`. All required fields are marked. Use the upcoming snippet to render the helm chart and apply it to the cluster:

```bash
helm template . | tee snitch.yaml | oc apply -f -
```
