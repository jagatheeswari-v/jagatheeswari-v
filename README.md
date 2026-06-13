class NetworkEngineer:
    def __init__(self):
        self.name         = "Your Name"
        self.location     = "Chennai, Tamil Nadu, India 🇮🇳"
        self.degree       = "B.E – Electronics & Communication Engineering"
        self.college      = "R.M.K. Engineering College (2023–2027)"
        self.cgpa         = 7.8

        self.stack = [
            "TCP/IP", "OSI Model", "VLANs", "OSPF", "BGP",
            "AWS VPC", "LoRa Mesh", "RF Systems", "Python", "C"
        ]

        self.currently_learning = [
            "5G NSA/SA Architecture  → NR air interface, gNB",
            "CCNP Deep-Dive          → Route redistribution, MPLS",
            "AWS Networking          → Direct Connect, Transit GW",
            "IoT Protocols           → MQTT, LoRaWAN, CoAP"
        ]

        self.fun_fact = (
            "Built a 5-node LoRa mesh that delivers SOS packets "
            "800 m+ apart with <3 s end-to-end latency — no cell towers needed."
        )

    def motto(self) -> str:
        return "Connect the unconnected. Secure the signal. Scale the network."

me = NetworkEngineer()
print(me.motto())
