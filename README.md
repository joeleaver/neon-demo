# neon-demo
Demo of Nervana's Python based Deep Learning framework, neon. Uses ansible to create and run docker image on an EC2 instance. Runs the mnist_mlp example.

To use: Copy `environment.yml` to `environment.yml.local` and adjust it for your environment. Then run the playbook: 

`ansible-playbook -i localhost playbook.yml`

Obviously, in real life you'd want to split this up into roles/tasks.

Check out https://github.com/NervanaSystems/neon
