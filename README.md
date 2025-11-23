# Ansible Role - Speedtest Tracker

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/speedtest-tracker?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/speedtest-tracker/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/speedtest-tracker?style=for-the-badge)](https://github.com/ursinn-ansible/speedtest-tracker/blob/main/LICENSE)

Docker Image: https://docs.linuxserver.io/images/docker-speedtest-tracker/

## Options

| Option | Default Value |
| ---- | ---- |
| role_speedtest_tracker_image | lscr.io/linuxserver/speedtest-tracker:latest |
| role_speedtest_tracker_container | speedtest-tracker |
| role_speedtest_tracker_puid | 1000 |
| role_speedtest_tracker_pgid | 1000 |
| role_speedtest_tracker_tz | Europe/Zurich |
| role_speedtest_tracker_app_key | |
| role_speedtest_tracker_app_url | |
| role_speedtest_tracker_speedtest_schedule | 0 */6 * * * |
| role_speedtest_tracker_speedtest_servers | |
| role_speedtest_tracker_dir | /opt/app-speedtest-tracker |
| role_speedtest_tracker_network | app-network |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/speedtest-tracker/blob/main/LICENSE) file for the full license text.
