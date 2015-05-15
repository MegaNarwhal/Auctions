# Auctions
Auctions is a Bukkit/Spigot plugin that allows players on servers to auction off their items for money. Current features include:

* Sealed auctions
* Herochat channel integration
* Broadcasts through the action bar
* Auction queues
* Spam reduction methods

Auctions is open source and is available under the GNU General Public License v3.

Compiling
--------
The project is written for Java 7 and can be compiled through the use of [Maven](http://maven.apache.org). To compile this project:

* Install [Maven](http://maven.apache.org)
* Clone the repository using `git clone https://github.com/sainttx/Auctions.git`
* Compile with maven using `mvn` or `mvn clean install`



Usage
--------
The subcommands for this plugin are as follows:

* `/auctions start <amount> <price> [increment] [autowin]`
* `/auctions info`
* `/auctions bid`
* `/auctions end`
* `/auctions cancel`
* `/auctions impound`
* `/auctions ignore`
* `/auctions spam`
* `/auctions queue`
* `/auctions toggle`
* `/auctions reload`
