.. Sphinx 0.6.2 will support the 'title' directive.  See
    http://bitbucket.org/birkenfeld/sphinx/changeset/036f2d008240/


JavaScript Toolkit for Rich Web Mapping Applications
====================================================

GeoExt brings together the geospatial know how of
`OpenLayers <http://openlayers.org>`_ with the user interface savvy of `Ext JS
<http://www.sencha.com/products/js/>`_ to help you build powerful desktop style GIS apps on
the web with JavaScript.

`Documentation <./docs.html>`_ | 
:ref:`Examples <examples>` | 
`Download <./downloads.html>`_ | 
`Development <http://trac.geoext.org/>`_

Using GeoExt
------------

See GeoExt in action.

.. cssclass:: execute

.. code-block:: javascript

    new Ext.Window({
        title: "GeoExt in Action",
        height: 280, width: 450, layout: "fit",
        items: [{
            xtype: "gx_mappanel",
            layers: [new OpenLayers.Layer.WMS(
                "Global Imagery", "http://maps.opengeo.org/geowebcache/service/wms",
                {layers: "bluemarble"}
            )],
            zoom: 1
        }]
    }).show();

Learn more about using GeoExt in your application by reading the
:doc:`documentation <docs>`.


GeoExt is Open Source
---------------------

GeoExt is available under the BSD license and is supported by a growing
community of individuals, businesses and organizations.

GeoExt depends on Ext JS, which can be used with a
`FLOSS exception for applications
<http://www.sencha.com/legal/open-source-faq/open-source-license-exception-for-applications/">_`
if your application is open source, or with the purchase of a commercial license otherwise.
GeoExt itself uses Ext JS with a `FLOSS exception for development
<http://www.sencha.com/legal/open-source-faq/open-source-license-exception-for-development/">_`.


.. toctree::
    :hidden:

    docs
    tutorials/index
    primers/index
    examples
    developer/index
    lib/index
    downloads
