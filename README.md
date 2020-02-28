# oclogs-sidecar
openshift sidecar - will collect oc logs and submit a zip to an endpoint

will require that your namespace default service account has view permission, so it can get read other pod's logs.
