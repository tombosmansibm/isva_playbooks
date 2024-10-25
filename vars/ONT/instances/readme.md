DPWAP0012E   An unsupported configuration entry was supplied.

ldap  bind-dn

'ssl', entries: [['ssl-keyfile', 'mp-default-webseald.kdb']]}
'ssl', entries: [['ssl-keyfile-stash', 'mp-default-webseald.sth']]}
'ssl', entries: [['ssl-keyfile-label', 'PD Server']]}
'ssl', entries: [['ssl-local-domain', 'DUOINT']]}
      - {method: set, stanza_id: 'PAM', entries: [['pam-library-directory', 'pam']]}
      - {method: set, stanza_id: 'aznapi-configuration', entries: [['cred-attribute-entitlement-services', 'TAM_CRED_POLICY_SVC'],
          ['cred-attribute-entitlement-services', 'TAM_CRED_ATTRS_SVC']]}
      - {method: set, stanza_id: 'http-updates', entries: [['update-cmd', 'mesa_config wga.trusteer']]}

seems not right
      - {method: set, stanza_id: 'junction', entries: [['enable-local-junction-scripts', 'false']]}