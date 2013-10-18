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

A notice about GeoExt versions
------------------------------

This website is about GeoExt 1.x, based on Ext JS 3. There is also a version of
GeoExt that is capable of working on top of the newest Ext JS: GeoExt 2.

Please refer to
`http://geoext.github.io/geoext2/ <http://geoext.github.io/geoext2/>`_ for
documentation, examples and more information about GeoExt 2.


GeoExt is Open Source
---------------------

GeoExt is available under the BSD license and is supported by a growing
community of individuals, businesses and organizations.


.. toctree::
    :hidden:

    docs
    tutorials/index
    primers/index
    examples
    developer/index
    lib/index
    downloads
