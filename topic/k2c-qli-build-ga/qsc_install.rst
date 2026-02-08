Install QSC Launcher
-----------------------

1. Go to the `Qualcomm Software Center <https://softwarecenter.qualcomm.com/#/catalog/item/Qualcomm_Software_Center>`__, and then select :guilabel:`Download`. The QSC Debian package (``.deb``) downloads to your machine.

2. To install the QSC Debian package using the Ubuntu GNOME GUI, install GDebi first. Run the following commands on your Linux host computer to install GDebi:

   ::

      sudo apt update
      sudo apt install gdebi

3. Right-click on the downloaded QSC Debian file and select :guilabel:`Open With GDebi Package Installer`.

   .. image:: ../../media/k2c-qli-build-ga/deb_gui_installer.png

4. Select :guilabel:`Install Package`.

5. Enter the password for the current user. In the following image, the current user is Ubuntu.

   .. image:: ../../media/k2c-qli-build-ga/current_user.png

6. To accept the license agreement, select :guilabel:`Next`.

7. Select :guilabel:`I ACCEPT` and `Next`. Wait for the installation to complete.

8. To find the Qualcomm Software Center, select :guilabel:`Show Applications`.

   .. image:: ../../media/k2c-qli-build-ga/show_apps.png
