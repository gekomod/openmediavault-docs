Plugins
=======

You can add more features & apps by simply selecting the software you need, we
call this plugins. Plugins are possible due to the modular design of |omv| and
are the preferred way to extend your NAS. While it is still possible to install regular software alongside |omv|, installing instead containerized software build with podman or Docker is highly recommended. This recommendation stems from many issues caused by later version updates that made |omv| or other software unusable due to introducing conflicting component dependencies. Plugins only exist for your
convenience.

Benefits
--------

Compared to adding regular software, plugins offer the following benefits:

* Easier to install - You just click on what you want.
* Easier to configure - it is often preconfigured so you don't have to.
* Automatic updates - ensure Stability & Security.
* A Webinterface - is added when needed for your ease of use.

Overview
--------

The following is the list of official plugins by |omv|. Their availability depends on the architecture on which |omv| is installed.

* **K8s**: Run your Docker containers in a lightweight Kubernetes environment.
* **MD**: Create, manage, and monitor software RAIDs based on Linux MD (Multiple Device) devices.
* **ClamAV**: Provides Clam AntiVirus (ClamAV). It is a free software, cross-platform and open-source antivirus software toolkit able to detect many types of malicious software, including viruses
* **Diskstats**: Complementary plugin to extend system statistics collection by adding I/O statistic graphs.
* **Forked-daap**: Provides a daap protocol music server.
* **FTP**: Provides a modular FTP/FTPS server.
* **LVM2**: LVM managing. Create volume groups and logical partitions.
* **NUT**: Controlling and configuring UPS. The driver support is based on NUT.
* **Onedrive** (amd64, arm64, armhf, i386 only): Synchronizing a shared folder with Microsoft OneDrive cloud storage.
* **Podman**: A tool for managing containers and images, volumes mounted into those containers, and pods made from groups of containers. Gives users the ability to pull the latest images of the containers that are used by some of the plugins
* **Shairport**: Provides Airtunes emulator. Stream music wirelessly to your iPod/iPad/iPhone/iTunes.
* **ShareRootFs**: Provides shared directories on root file system.
* **SNMP**: Provides Simple Network Management Protocol (SNMP). SNMP is an Internet Standard protocol for collecting and organizing information about managed devices on IP networks.
* **TFtp**: Provides Trivial File Transfer Protocol (TFTP). TFTP is a simple lockstep File Transfer Protocol which allows a client to get a file from or put a file onto a remote host.
* **USB Backup**: Backup internal data to external disks on scheduled basis or on plug drive event.
* **BCache**: Use an SSD as a read/write cache for another block device.

Podman container-based plugins:

* **FileBrowser**: File managing interface.
* **OwnTone**: Provides a DAAP (iTunes), MPD (Music Player Daemon) and RSP (Roku) media server.
* **PhotoPrism**: AI-powered app for browsing, organizing & sharing your photo collection.
* **S3**: MinIO based high-performance, S3 compatible object storage.
* **WeTTY**: Terminal access in browser over HTTP/HTTPS.

.. _plugin_3rd_party:

3rd party
---------

An overview of the third party plugin list can be found at `omv-extras.org <http://www.omv-extras.org/>`_.
