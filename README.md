# CCNA2020_interVlans_thruRouter

vlan 內的影格封包是透過泛洪和廣播轉發的，但如果 vlan 外的不同的虛擬區域網路的封包則要透過路由傳遞轉發。

# Local or Remote

關於影格是否為本地或是遠端，由是否隸屬同一個 Vlan 而定。
倘若影格在不同的 Vlan 則為遠端。
此時需要透過路由才能進入到不同的廣播網域 Broadcast Domain。
