# Security Group VPC Policy
This library, provides prescriptive Terraform policies that can be used to establish secure Terraform configuration for Amazon Web Services. The policies that are contained in this library are based on the [CIS Amazon Web Services Benchmarks](https://www.cisecurity.org/benchmark/amazon_web_services). Terraform Cloud/Enterprise users can use the policies in this library to establish a foundational level of security for the services that they are adopting in Amazon Web Services.

> **NOTE:**
>
> This Policy Library is not an exhaustive list of all of possible security configurations and architecture that is available in Amazon Web Services. If you have questions, comments, or have identified ways for us to improve this library, please create [a new GitHub issue](https://github.com/hashicorp/policy-library-aws-networking-terraform/issues/new/choose).
>
> Alternatively, We welcome any contributions that improve the quality of this library! To learn more about contributing and suggesting changes to this library, refer to the [contributing guide](https://github.com/hashicorp/policy-library-aws-networking-terraform/blob/main/CONTRIBUTING.md).

---

## Policies included

-  Ensure the default security group of every VPC restricts all traffic ([docs](https://github.com/hashicorp/policy-library-aws-networking-terraform/blob/main/docs/policies/restrict-all-vpc-traffic-acl-rules.md) | [code](https://github.com/hashicorp/policy-library-aws-networking-terraform/blob/main/policies/restrict-all-vpc-traffic-acl-rules/restrict-all-vpc-traffic-acl-rules.sentinel))

---
