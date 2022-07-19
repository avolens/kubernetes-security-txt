# Kubernetes Security API endpoint

Possible Kubernetes KEP for creating a /security endpoint with contact information for security researchers.

## Motivation

If a security researcher finds a misconfigured Kubernetes API or Kubelet endpoint and wants to report it to the appropriate company, it can be very difficult to find the company running the Kubernetes API or Kubelet without gaining deep access to the cluster. The security researcher has only a few ways to find out if the Kubelet or Kubernetes API belongs to a certain company.

## Improvement

For web pages, there is the concept of the [security.txt](https://github.com/securitytxt/security-txt) file to [RFC9116](https://www.rfc-editor.org/rfc/rfc9116). This would also be conceivable for Kubernetes. For the Kubernetes API and the Kubelet there should be a `/security` endpoint containing the appropriate contact information.
