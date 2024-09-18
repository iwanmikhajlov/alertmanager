# Alertmanager w/ Telegram group topics support

To build you need:

- go v1.2x
- node 18.X
- make

Just clone this branch, and do cd alertmanager/ && make build

As a result you will get two binaries: alertmanager and amtool

Now you can use message_thread_id keyword in recievers section of alertmanager.yaml
Build a docker image, or create a systemd service, whatever you like
