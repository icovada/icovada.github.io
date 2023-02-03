<script setup lang="ts">
</script>

<template>
  <div class="col-12 col-md-8 col-xxl-5 d-flex p-2 p-md-5 flex-fill flex-column text-bg-dark main-section">
    <div class="container">
      <div class="d-flex flex-column section text-bg-dark border border-light-subtle rounded my-2">
        <h1 class="py-4 fs-2 text-center">Work</h1>
        <ul class="timeline">
          <li class="block">
            <div class="fw-bold">Senior Implementation Engineer @ <a href="https://services.global.ntt">NTT Ltd</a>
            </div>
            <div class="date">2022-now</div>
            <p>Currently member of the DC Design team @ major european ISP</p>
          </li>

          <li class="block">
            <div class="fw-bold">Implementation Engineer @ <a href="https://services.global.ntt">NTT Ltd</a></div>
            <div class="date">2018-2022</div>
            <p class="fst-italic">Network engineer on campus, DC and Service Provider technologies</p>
            <p>Main projects and customers:</p>
            <ul>
              <li><a href="https://www.snam.it">SNAM</a>: DC migration from classical Nexus to Cisco ACI. Wrote <i
                  class="text-info">Python</i> script to parse layer-2 Nexus configurations and re-create relevant port
                bindings on ACI</li>
              <li><a href="https://www.gruppoveronesi.it/">Gruppo Veronesi</a>: Followed several LAN refurbishments and
                new site activations, taking part in defining policies for the entire network</li>
              <li><a href="https://www.gruppoveronesi.it/">Gruppo Veronesi</a>: LAN Segmentation and config cleanup. In
                charge of a small team, we analyzed and fixed configurations of over 500 network devices to bring them
                up to policy. In total, 20000 ports were analysed and attached clients, still mostly in VLAN 1, were
                migrated to their correct VLAN to improve security through segmentation. Topology discovery and config
                parsing and changes were done through my library <a class="text-info fw-bold"
                  href="https://github.com/icovada/netwalk">Netwalk</a> combined with <i class="text-info">NetBox</i>
                and a <i class="text-info">Jenkins pipeline</i></li>
              <li><a href="https://www.esselunga.it">Esselunga</a>: Web middleware built on <i
                  class="text-info">Django</i> with Bootstrap frontend to simplify day-by-day operations on Cisco ACI
              </li>
            </ul>
            <p>Side projects: <a href="/side-projects/metamonitor">Meta Monitor</a>, <a
                href="/side-projects/stageit">StageIT</a></p>
          </li>

          <li class="block">
            <div class="fw-bold">Network and Collaboration Engineer @ <a href="https://lutech.group">Lutech</a></div>
            <div class="date">2013-2018</div>
            <p class="fst-italic">My first fole, starting as an intern and progressing to Engineer on Cisco network and
              collaboration technologies.</p>
            <p>Main projects and customers:</p>
            <ul>
              <li><a href="https://www.fincantieri.it">Fincantieri</a>: LAN refurbishment for two shipyards. Took part
                as junior member of a team, changing switches on the field and investigating issues.</li>
              <li><a href="https://www.mirogliogroup.com/">Miroglio</a>: Phone system migration from traditional POTS
                lines to <i class="text-info">Cisco Call Manager</i>. Through the years I've gone from following shop
                activations and migrations to taking charge of the migration of all of the offices and productive
                plants, making desing choices, becoming the reference point for the customer</li>
            </ul>
          </li>

          <li class="block">
            <div class="fw-bold">Random stuff on my server @ Home</div>
            <div class="date">2010-2013</div>
            <p>Stuff I've played with in no particular order: debian iptables php syslog apache2 squid cron ossec mysql
              phpmyadmin webmin postfix dovecot openvpn quagga samba lxc zfs netatalk avahi</p>
          </li>
        </ul>

      </div>

      <div class="d-flex flex-column section text-bg-dark border border-light-subtle rounded my-2">
        <h1 class="py-4 fs-2 text-center">Certifications</h1>
        <ul class="timeline">
          <li class="block">
            <div class="fw-bold">CCNP Data Center</div>
            <div class="date">2022</div>
          </li>

          <li class="block">
            <div class="fw-bold">Cisco Certified Specialist - Data Center ACI Implementation</div>
            <div class="date">2021</div>
          </li>

          <li class="block">
            <div class="fw-bold">Oracle Communications Session Border Controller 7 Basic Certified Implementation
              Specialist</div>
            <div class="date">2020</div>
          </li>

          <li class="block">
            <div class="fw-bold">CCNP Routing and Switching (now Enterprise)</div>
            <div class="date">2019</div>
          </li>

          <li class="block">
            <div class="fw-bold">CCNA Voice</div>
            <div class="date">2013</div>
          </li>

          <li class="block">
            <div class="fw-bold">CCNA R&S</div>
            <div class="date">2013</div>
          </li>
        </ul>
      </div>
    </div>
  </div>

</template>

<style scoped>
.sidebar {
  overflow-y: scroll;
}
</style>