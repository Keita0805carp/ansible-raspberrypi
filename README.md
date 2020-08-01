# ansible-raspberrypi

ラズパイセットアップ自分用

---

## Ping

    ansible -i hosts RaspberryPi-Zero -m ping

## Run

    ansible-playbook -i hosts site.yaml --ask-become-pass

`--ask-become-pass` :  Ask root Password
