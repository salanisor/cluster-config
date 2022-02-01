List info regarding upstream url, current channel, available channels, and updates such as image versions and their 256sha

    oc adm upgrade

Update spec accordingly.

spec:
  channel: stable-4.9
  clusterID: a20f1746-c785-466e-9b32-4377eb77cfc2
  desiredUpdate:
    image: quay.io/openshift-release-dev/ocp-release@sha256:0f72e150329db15279a1aeda1286c9495258a4892bc5bf1bf5bb89942cd432de
    version: 4.9.11
  upstream: https://api.openshift.com/api/upgrades_info/v1/graph
