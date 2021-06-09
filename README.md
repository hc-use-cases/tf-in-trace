# tf-in-trace
Terraform in trace mode


## providers directory

```bash
agrant@tf-in-trace:/vagrant$ export TF_LOG=TRACE && terraform init
2021-06-09T13:32:02.193Z [DEBUG] Adding temp file log sink: /tmp/terraform-log508370920
2021-06-09T13:32:02.193Z [INFO]  Terraform version: 1.0.0
2021-06-09T13:32:02.193Z [INFO]  Go runtime version: go1.16.4
2021-06-09T13:32:02.193Z [INFO]  CLI args: []string{"/usr/local/bin/terraform", "init"}
2021-06-09T13:32:02.193Z [TRACE] Stdout is a terminal of width 165
2021-06-09T13:32:02.193Z [TRACE] Stderr is a terminal of width 165
2021-06-09T13:32:02.193Z [TRACE] Stdin is a terminal
2021-06-09T13:32:02.193Z [DEBUG] Attempting to open CLI config file: /home/vagrant/.terraformrc
2021-06-09T13:32:02.193Z [DEBUG] File doesn't exist, but doesn't need to. Ignoring.
2021-06-09T13:32:02.194Z [DEBUG] ignoring non-existing provider search directory terraform.d/plugins
2021-06-09T13:32:02.194Z [DEBUG] ignoring non-existing provider search directory /home/vagrant/.terraform.d/plugins
2021-06-09T13:32:02.194Z [DEBUG] ignoring non-existing provider search directory /home/vagrant/.local/share/terraform/plugins
2021-06-09T13:32:02.194Z [DEBUG] ignoring non-existing provider search directory /usr/local/share/terraform/plugins
2021-06-09T13:32:02.194Z [DEBUG] ignoring non-existing provider search directory /usr/share/terraform/plugins
```
