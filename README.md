# Server for ssh-tunnel-client role

`ssh_tunnel_server_user` - default is `ssh_tunnel`
`ssh_tunnel_server_authorized_keys` - list of pubkey strings 
`ssh_tunnel_server_set_keepalive` - whether to set the sshd ClientAlive* options
`ssh_tunnel_server_alive_interval` - default: 30 (set only when `ssh_tunnel_server_set_keepalive` is true)
`ssh_tunnel_server_alive_count_max` - default: 2 (set only when `ssh_tunnel_server_set_keepalive` is true)