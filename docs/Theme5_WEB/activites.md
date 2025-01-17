![image](data/html_css.webp){: .center}

Les pages Web sont écrites dans le langage HTML (HyperText Language Markup, soit « langage de balisage d'hypertexte ») qui est un langage de balises (markup signifie balise en anglais).  

Les feuilles de style en cascade, généralement appelées CSS de l'anglais Cascading Style Sheets, forment un langage informatique qui décrit la présentation des documents HTML, elles donnent du style aux pages web ecrites en HTML.

!!! info
    Le langage HTML a été inventé et développé par Tim Berners-Lee et Robert Cailliau au début des années 1990. C'est en 1993 que la version initiale de HTML apparaît. Depuis 2007, c'est la version 5 de HTML qui est utilisée, on parle de HTML 5.

**Dans cette séance, vous allez découvrir ce qu'est une balise puis vous écrirez votre première page WEB en HTML-CSS.**

## Activité 1
[ici](https://capytale2.ac-paris.fr/web/c/cd32-3672599){: target = "_blank"}

## Activité 2
[ici](https://capytale2.ac-paris.fr/web/c/eba1-3675894){: target = "_blank"}

## Activité 3
[ici](https://capytale2.ac-paris.fr/web/c/63f6-3676180){: target = "_blank"}

!!! info
	- Voici les attendus pour l'activité 3 :  
	Votre mini site doit contenir 2 pages au minimum, dans lesquelles je veux :  
		
		Vu dans les activités 1 et 2 : 
		- des titres h1 et h2,
		- des paragraphes
		- des images 
		- les sources des images utilisées sont mentionnées et appartiennent au domaine public ou sont en licence libre
		- des liens (navigation entre vos pages)
		- du style (fichier CSS)
		
		Non vu mais à rechercher dans les ressources données dans l'activité 3 :
		- une liste ordonnée
		- une liste  non-ordonnée
		- un lien vers une page du web
		- une vidéo (source mentionnée)

	| Élément à vérifier                               | Vu dans les activités 1 et 2 | Non vu mais à rechercher dans les ressources données dans l'activité 3 | Barème |
	|-------------------------------------------------|------------------------------|-------------------------------------------------------------------------|--------|
	| **Titres h1 et h2**                             | ✅                            |                                                                         | 5/5    |
	| **Paragraphes**                                 | ✅                            |                                                                         | 5/5    |
	| **Images**                                      | ✅                            |                                                                         | 5/5    |
	| **Sources des images utilisées (domaine public ou licence libre)**| ✅                            |                                                                         | 5/5    |
	| **Liens (navigation entre pages)**              | ✅                            |                                                                         | 5/5    |
	| **Style (toutes les techniques vues; fichier CSS)**                         | ✅                            |                                                                         | 5/5    |
	| **Liste ordonnée**                              |                              | ✅                                                                      | 5/5    |
	| **Liste non-ordonnée**                          |                              | ✅                                                                      | 5/5    |
	| **Lien vers une page du web**                   |                              | ✅                                                                      | 5/5    |
	| **Vidéo (source mentionnée)**                   |                              | ✅                                                                      | 5/5    |

	## Explications

	1. **Titres h1 et h2**
	   Les titres sont utilisés pour structurer le contenu d'une page. Le titre principal est généralement un `<h1>`, et les sous-titres sont des `<h2>`, permettant une hiérarchisation claire des informations.  
	   Exemple :  
	   
	   # Titre principal
	   ## Sous-titre
	   
		 ```html
		 <h1>Titre Principal</h1>
		 <h2>Sous-Titre</h2>
		 ```

	2. **Paragraphes**
	   - Les paragraphes permettent de structurer le texte en blocs. Chaque paragraphe est entouré par la balise `<p>`.
	   - Exemple : 
		 ```html
		 <p>Ceci est un paragraphe de texte.</p>
		 ```

	3. **Images**
	   - Les images peuvent être insérées avec la balise `<img>`, et il est important de mentionner la source des images, surtout si elles proviennent du domaine public ou sont sous licence libre.
	   - Exemple :
		 ```html
		 <img src="image.jpg" alt="Description de l'image">
		 ```

	4. **Sources des images utilisées (domaine public ou licence libre)**
	   - Il est nécessaire de s'assurer que les images utilisées proviennent du domaine public ou sont sous licence libre. Cela garantit qu'elles peuvent être utilisées sans violer les droits d’auteur.
	   - Exemple de source mentionnée :
		 ```html
		 <p>Image fournie par <a href="https://...">source</a> sous licence Creative Commons.</p>
		 ```

	5. **Liens (navigation entre pages)**
	   - Les liens permettent de naviguer entre différentes pages ou vers des ressources externes. On utilise la balise `<a>` pour insérer des liens.
	   - Exemple :
		 ```html
		 <a href="page.html">Cliquez ici pour accéder à la page suivante</a>
		 ```

	6. **Style (fichier CSS)**
	   - Le fichier CSS permet de définir le style de la page (couleurs, polices, espacements, etc.).
	   

	7. **Liste ordonnée**
	   - Une liste ordonnée est utilisée pour présenter des éléments dans un ordre précis, généralement numéroté. Elle est créée avec la balise `<ol>`, et chaque élément de la liste est entouré de `<li>`.
	   - Exemple :
		 ```html
		 <ol>
		   <li>Premier élément</li>
		   <li>Deuxième élément</li>
		 </ol>
		 ```

	8. **Liste non-ordonnée**
	   - Une liste non-ordonnée est utilisée pour présenter des éléments sans ordre particulier, avec des puces. Elle est créée avec la balise `<ul>`, et chaque élément de la liste est entouré de `<li>`.
	   - Exemple :
		 ```html
		 <ul>
		   <li>Premier élément</li>
		   <li>Deuxième élément</li>
		 </ul>
		 ```

	9. **Lien vers une page du web**
	   - Un lien vers une page du web permet d’accéder à des ressources externes. Il est inséré à l’aide de la balise `<a>` avec l'attribut `href` pointant vers l'URL souhaitée.
	   - Exemple :
		 ```html
		 <a href="https://www.wikipedia.com">Visitez notre site</a>
		 ```

	10. **Vidéo (source mentionnée)**
		- Les vidéos peuvent être insérées avec la balise `<video>`, et il est essentiel de mentionner la source de la vidéo, notamment si elle provient d'une plateforme externe.
		- Exemple :
		  ```html
		  <video src="video.mp4" controls>
			Votre navigateur ne supporte pas les vidéos HTML5.
		  </video>
		  ```


<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/GqD6AiaRo3U?si=XVLZhX-yoCj6R1lU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



## Explications

1. **Titres h1 et h2**
   - Les titres sont utilisés pour structurer le contenu d'une page. Le titre principal est généralement un `#` (pour `h1`), et les sous-titres sont des `##` (pour `h2`), permettant une hiérarchisation claire des informations.
   - Exemple :
     ```
     # Titre Principal
     ## Sous-Titre
     ```

2. **Paragraphes**
   - Les paragraphes permettent de structurer le texte en blocs. Chaque paragraphe est simplement écrit sur une nouvelle ligne, avec un espace entre les blocs pour que le texte soit bien séparé.
   - Exemple :
     ```
     Ceci est un paragraphe de texte.
     ```

3. **Images**
   - Les images peuvent être insérées avec la syntaxe Markdown en utilisant la syntaxe `![alt text](url)`. Il est important de mentionner la source des images, surtout si elles proviennent du domaine public ou sont sous licence libre.
   - Exemple :
     ```
     ![Description de l'image](image.jpg)
     ```

4. **Sources des images utilisées (domaine public ou licence libre)**
   - Il est nécessaire de s'assurer que les images utilisées proviennent du domaine public ou sont sous licence libre. Cela garantit qu'elles peuvent être utilisées sans violer les droits d’auteur.
   - Exemple de source mentionnée :
     ```
     Image fournie par [source.com](https://source.com) sous licence Creative Commons.
     ```

5. **Liens (navigation entre pages)**
   - Les liens permettent de naviguer entre différentes pages ou vers des ressources externes. On utilise la syntaxe `[Texte du lien](URL)` pour insérer des liens en Markdown.
   - Exemple :
     ```
     [Cliquez ici pour accéder à la page suivante](page.html)
     ```

6. **Style (fichier CSS)**
   - Le style CSS n'est pas directement écrit en Markdown, mais vous pouvez mentionner un fichier CSS dans un document HTML généré par le Markdown, ou inclure un lien vers un fichier externe.
   - Exemple :
     ```
     [Lien vers le fichier CSS](styles.css)
     ```

7. **Liste ordonnée**
   - Une liste ordonnée est utilisée pour présenter des éléments dans un ordre précis, généralement numéroté. Elle est créée avec des chiffres suivis d'un point.
   - Exemple :
     ```
     1. Premier élément
     2. Deuxième élément
     ```

8. **Liste non-ordonnée**
   - Une liste non-ordonnée est utilisée pour présenter des éléments sans ordre particulier, avec des puces. Elle est créée avec des tirets `-`, des astérisques `*`, ou des plus `+`.
   - Exemple :
     ```
     - Premier élément
     - Deuxième élément
     ```

9. **Lien vers une page du web**
   - Un lien vers une page du web permet d’accéder à des ressources externes. Il est inséré à l’aide de la syntaxe `[Texte du lien](URL)`.
   - Exemple :
     ```
     [Visitez notre site](https://www.example.com)
     ```

10. **Vidéo (source mentionnée)**
    - En Markdown, il n'est pas possible d'insérer directement une vidéo comme en HTML. Cependant, vous pouvez ajouter un lien vers la vidéo ou intégrer une vidéo via une plateforme comme YouTube en utilisant un lien.
    - Exemple :
      ```
      [Voir la vidéo](https://www.youtube.com/watch?v=videoID)
      ```

