# 📦 ChestShop

![](../.assets/citybuild/chestshop/intro/shop-intro.png)

### Wie benutzt man einen ChestShop?

Klicke einfach mit der **rechten Maustaste** auf das Schild, um etwas zu kaufen, und mit der **linken Maustaste**, um etwas zu verkaufen.

### Wie erstellt man einen ChestShop?

1. Platziere eine Kiste
2. Setze ein Schild an die Kiste&#x20;
3. Beschrifte das Schild wie folgt:&#x20;

![](../.assets/citybuild/chestshop/creation/shop-creation.png)

* Freilassen
* Menge der verkaufenden/kaufenden Items
* B (Verkaufspreis) : S (Ankaufspreis)
* ? (Die Item-ID wird automatisch eingetragen)

![](../.assets/citybuild/chestshop/result/shop-result.png)

### Welche Befehle gibt es für den ChestShop?

{% tabs %}
{% tab title="Java Edition" %}
**/iteminfo** -> Hiermit erhält man über das Item in seiner Hand alle relevanten Informationen.

**/iteminfo \<id/name>** -> Hiermit erhält man Informationen über das Item, welches angegeben wurde.\
**/shopinfo** -> Hiermit erhält man Informationen über den betrachteten Shop.\
**/cstoggle** -> Hiermit kann man die Kauf-/Verkaufsbenachrichtigungen

aktivieren/deaktiveren.
{% endtab %}

{% tab title="Bedrock Edition" %}
**/shopcreate** -> Hiermit wird ein ChestShop erstellt.

**/iteminfo** -> Hiermit erhält man über das Item in seiner Hand alle relevanten Informationen.

**/iteminfo** \<id/name> -> Hiermit erhält man Informationen über das Item, welches angegeben wurde.\
**/shopinfo** -> Hiermit erhält man Informationen über den betrachteten Shop.\
**/cstoggle** -> Hiermit kann man die Kauf-/Verkaufsbenachrichtigungen aktivieren/deaktiveren.
{% endtab %}
{% endtabs %}