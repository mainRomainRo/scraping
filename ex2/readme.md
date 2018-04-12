##################################################

Programme : Ruby :

##################################################

Infos : Scrapping 
Recupere toutes les infos permet de connaitre le cours de la monnaie

--------------------------------------------------
Requis : 
	require 'nokogiri'   # gem nokogiri
	require 'open-uri'   # gem open-uri

--------------------------------------------------
Nos balises :
	doc = Nokogiri::HTML(open("https://coinmarketcap.com/all/views/all/"))      # liens d'ouverture
	doc.css('a.currency-name-container').each_with_index do | prix, nombre |    # Liens manip 

--------------------------------------------------

Permet de gere le temps d'affichage entre les differentes crypto :
sleep 0.5 

--------------------------------------------------
