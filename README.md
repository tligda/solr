Description
===========
Installs and configures Solr. Solr Version, Tomcat or Jetty, single or multicore are set as attributes with these defaults:


Requirements
============

Attributes
==========

`node[:solr][:installed]` - default `false`
`node[:solr][:version]` - default `3.5.0`
`node[:solr][:container]` - default `tomcat`
`node[:solr][:multicore]` - default `false`
`node[:solr][:core_names]` - default nil
`node[:solr][:install_path]` - default `/home/admin/solr`
`node[:solr][:root_path]` - default `/data`
`node[:solr][:data_path]` - default `/data/solrdata`
`node[:solr][:velocity_enable]` - default `false`

Usage
=====
Include this recipe when you want to install Apache Solr.
