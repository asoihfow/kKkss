bot.command({
  name: "avatar",
  code: `
  $title[📷 Aqui está!]
  $description[[Clique aqui para baixar a imagem]($userAvatar[$mentioned[1]])]
  $image[$userAvatar[$mentioned[1]]]
  $color[RANDOM]
  `
})
