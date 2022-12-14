A new critical security flaw is released for Amazon Elastic Container Registry that can be potentially exploited to stage a multitude of attacks. ECR is a container image registry service similar to the Docker images or containers.

The vulnerability lies with internal APIs used which have a flaw that could lead to denial of service, data exfiltration, lateral movement, privilege escalation and other multivariate attack paths. The detailed research is given in the link below.

This has been characterized as  deep software supply chain attack. A strengthening guide for ECR by AWS should be referenced by the end users when installing such services to production. The patch for it has been released and customers are updated to install it as soon as possible. It also shows the importance of auditing the process of third party service providers for the companies and being aware of the latest vulnerabilities in the industry.

Disclaimer: A quick video for this is in production.

Links:

[https://thehackernews.com/2022/12/serious-attacks-could-have-been-staged.html](https://thehackernews.com/2022/12/serious-attacks-could-have-been-staged.html)

[https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html](https://docs.aws.amazon.com/AmazonECR/latest/userguide/security.html)
