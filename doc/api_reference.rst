.. UPS Integration with OpenERP documentation master file, created by
   sphinx-quickstart on Wed Jul  6 13:03:15 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
   

API Reference
#############

contents:

.. toctree::
   :maxdepth: 5


.. currentmodule:: ups

.. automodule:: res.company

Company
"""""""
    .. autoclass:: ResCompany
    
        .. automethod:: get_ups_credentials
        
        .. automethod:: get_ups_uoms
        
        .. automethod:: get_ups_shipper


.. automodule:: res.partner.address

Partner
"""""""
    
    .. autoclass:: ResPartnerAddress

        .. automethod:: address_to_ups_dict


.. automodule:: ups.codes

UPS Codes
"""""""""
    .. autoclass:: UpsCodes


.. automodule:: ups.shippingregister

Shipping Register
"""""""""""""""""
    .. autoclass:: UpsShippingRegister
