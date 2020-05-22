# AWS VPC module for Terraform

A lightweight VPC module for Terraform

## Usage

module "vpc" {
	source = "https://github.com/peyunco/tf_vpc.git"
	name = "vpc_name"
	cidr = "10.0.0.0/16"
	public_subnet = "10.0.1.0/24"
}

See `interface.tf` for additional configurable variables.

## License

MIT 