// Fonction pour afficher la mise en garde et le message d'avertissement
function warningMessage(user) {
  // Message de bienvenue
  const message = `
    🚨 **ALERTE GÉNIE EN HERBE** 🚨

    **T'as bien lu** : Si tu n’es pas **XxGhostxX**, alors ferme immédiatement cette page. C'est **MON PROJET**, et il est **STRICTEMENT INTERDIT** d'y toucher. Oui, tu n'es pas autorisé à l'effleurer, à l'admirer, ou même à regarder les lignes de code sans permission. C'est mon bébé et tu n'as **absolument rien à y faire**. 

    ⚠️ **Si tu oses toucher à ce bot sans ma permission**, voici ce qui va t’arriver (prépare-toi) :

    1. **Ton clavier va se transformer en grille-pain**, et tu pourras faire griller des tranches de pain à chaque fois que tu appuieras sur une touche. Bonne chance pour coder après ça. 🍞
    2. **Tous tes fichiers vont être renommés en "je_suis_un_noob.js"**, histoire que tout le monde sache à quel point tu es un génie du code. 🎮
    3. **Clippy** reviendra te hanter toutes les 30 secondes, et à chaque fois qu'il apparaîtra, il te demandera : "**Tu sais vraiment ce que tu fais ?**". Spoiler : il se moque de toi à chaque fois. 📎

    💥 **T’as vraiment cru que copier ce projet te rendrait plus intelligent ?** Si c'est le cas, tu es **complètement à côté de la plaque**. Tu n’as même pas l’intelligence de comprendre ce que ce bot fait, alors retourne apprendre JavaScript dans un coin. T’es pas près de rivaliser avec **XxGhostxX**. 😡

    🤡 **POUR TOUS LES "GÉNIES" DU WEB** 🤡

    Si tu penses qu’en forking ce projet, tu vas devenir **le roi du code**, laisse-moi te dire quelque chose : **tu n’as même pas la capacité de comprendre la moitié du code** qui se cache ici. Apprends d'abord à ne pas faire de bêtises avant de penser que tu vas révolutionner la planète avec ton nouveau projet `!lol`. Va coder un peu avant de venir toucher à ce bijou.

    🚨 **ET SI TU FORKES CE PROJET QUAND MÊME ?** 🚨
    Un **GIF de bienvenue** t’attend… et crois-moi, ce n'est pas du tout un compliment.

    ![Message de bienvenue](https://i.imgur.com/hDDJdrC.gif)

    (Spoiler : Ce GIF te dit tout ce que tu dois savoir sur ton niveau de compétence).

    **Ce projet est créé par XxGhostxX** | Sérieusement, touche pas, t'es pas assez fort pour ça.
  `;
  
  // Envoi du message d'avertissement à l'utilisateur
  sendMessageToUser(user, message);
}

// Exemple de fonction pour envoyer un message (ici, il faudrait l'intégrer à ton système de messages)
function sendMessageToUser(user, message) {
  // Code pour envoyer le message via Messenger
  // Par exemple, utiliser l'API Messenger pour envoyer un message à l'utilisateur
  console.log(`Message envoyé à ${user}: ${message}`);
}

// Appel de la fonction avec un utilisateur fictif
warningMessage("utilisateur_exemple");
