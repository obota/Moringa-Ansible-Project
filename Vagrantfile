Vagrant.configure("2") do |config|
  config.vm.box = "dummy"

  config.vm.provider "aws" do |aws, override|
    aws.access_key_id = "AKIAUDJFWTUWBYDAGQFP"
    aws.secret_access_key = "HClmMZTTffEy5ziUjYNnF0RJrmfhvDgTOOJv4wfO"
    aws.instance_type = "t2.micro"
    aws.region = "us-east-1"
    aws.ami = "ami-0dba2cb6798deb6d8"  # Ubuntu 20.04 LTS
  end
end
