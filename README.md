Packer-Templates
----------------
Contains configs for different packer build that might be useful for testing or generating mostly baked images on demand.

Acknowledgements
----------------

* [Elasticdog / packer-arch](https://github.com/elasticdog/packer-arch)
* [SocialGeeks / packer-boxes](https://github.com/SocialGeeks/packer-boxes)

Random Notes
------------
```json
"iso_url": "https://mirrors.kernel.org/archlinux/iso/2014.05.01/archlinux-2014.05.01-dual.iso",
 "wget http://{{ .HTTPIP }}:{{ .HTTPPort }}/install.sh && chmod +x /tmp/install.sh && /tmp/install.sh<enter>"

```


