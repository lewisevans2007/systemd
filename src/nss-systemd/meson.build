# SPDX-License-Identifier: LGPL-2.1-or-later

modules += [
        nss_template + {
                'name' : 'nss_systemd',
                'conditions' : ['ENABLE_NSS_SYSTEMD'],
                'sources' : files(
                        'nss-systemd.c',
                        'userdb-glue.c',
                ),
                'link_depends' : files('nss-systemd.sym'),
        },
]
