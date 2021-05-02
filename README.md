# rust_port_sniffer_cli
 
A port scanner is an application designed to probe a server or host for open ports. Such an application may be used by administrators to verify security policies of their networks and by attackers to identify network services running on a host and exploit vulnerabilities.


Use:
-> `cargo run -- -h` or `cargo run -- -help`to show help message
-> `cargo run -- -j <number_threads> <ipAddr>`to select how many threads you want
-> `cargo run -- <ipAddr>` 

**OBS: Use number_threads between 1 and 65535. We recommends that you use 3000 threads.