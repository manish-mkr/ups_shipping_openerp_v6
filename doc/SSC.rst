Standalone Shipping Client
##########################

In the Standalone usage you can create custom shipments using the OpenERP 
interface. To access this functionality open *Warehouse >> UPS* Shipping Register.

.. figure:: _images/Screenshot8.png
   :width: 1000

   **Standalone Mode Menu**

.. figure:: _images/Screenshot9.png
    :width: 1000
    
    **Example in Standalone Mode** : This figure shows how a new package is
    created. The fields are explained as below:   

    * ``Shipper Address`` : The address of the Shipper
    * ``Shipping Address`` : The shipping address to which the product has to be
      delivered.
    * ``From Address`` : The address from where the shipping has to be done.
    * ``Service Type`` : The Service Type

After providing the necessary information, click on **Request**. Billed
weight and total amount will be fetched from UPS. 

.. figure:: _images/Screenshot16.png
    :width: 1000
    
    **Confirmed Shipping Awaiting Acceptance**

.. figure:: _images/Screenshot17.png
   :width: 1000

   **Billed Weight & Amount from UPS** : Now go to ``UPS Response Details`` tab
   to view the *Billed Weight*, *Total Amount* etc.


Click on **Accept** in the ``UPS Response Details`` tab. A new record
will be created in the `UPS Shipping Register`. Double click the newly
generated record.

.. figure:: _images/Screenshot18.png
   :width: 1000
    
   **Tracking Number** : As the record is selected a new dialog box **OpenERP -
   Packages** will pop-up. From this Output the label can be downloaded.
   Click on **Open** to view the label.

.. figure:: _images/Screenshot19.png
   :width: 1000
    
   **Shipping Label** : The label will open in your preferred image viewer.

