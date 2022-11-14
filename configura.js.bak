const fs = require('fs')
const chalk = require('chalk')

global.wlcm = []
global.region = 'Brasil'
//=================================================//
//—————「 Configure aqui  」—————//

global.dono = ['559784388524']
global.premium = ['559784388524']
global.prefixo = ['.']
global.reagir1 = '🔥'
global.reagir2 = '🤬'
global.reagir3 = '🤣'
global.reagir4 = '📌'
global.packname = '🔥νєησм'
global.footer = 'Venom Mods' 
global.author = 'мσ∂ѕ🔥'
global.QrNome = './VenomPrivat'

global.resposta = {
  espere: '*Carregando... tenha Paciência *_', 
  privado: 'Recurso usado apenas para um bate-papo privado!',
  dono: '*Este comando so pode se usado pelo meu dono*',  
  grupo: '*Este comando fucionar apenas em grupos*',
  myadm: '*Eu preciso se um adm do grupp para executar este comando*',
  adm: '*Este comando so é para adm do grupo*',
  sucesso: '*Feitinho*', 
  banido: '*❗Você não pode mais usar os comando do bot entre em contato com o proprietário*',
  sempix: `❗Acesso negado❗\neste comando so fuciona se você pagar via pix\ncaso queira chame o desenvolvedor venom neste link\n\nhttps://wa.me/559784388524`, 
  bot: 'Recurso so para usuários o bot',

}
//=================================================//
global.doc1 = 'application/vnd.openxmlformats-officedocument.presentationml.presentation'
global.doc2 = 'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet'
global.doc3 = 'application/vnd.openxmlformats-officedocument.wordprocessingml.document'
global.doc4 = 'application/zip'
global.doc5 = 'application/pdf'
global.doc6 = 'application/vnd.android.package-archive'
global.f1 = 'application/vnd.openxmlformats-officedocument.presentationml.presentation'
global.f2 = 'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet'
global.f3 = 'application/vnd.openxmlformats-officedocument.wordprocessingml.document'
global.f4 = 'application/zip'
global.f5 = 'application/pdf'
global.f6 = 'application/vnd.android.package-archive'
//=================================================//
global.thumb = fs.readFileSync("./dados/imagem/venom.jpg")
global.videovenom = fs.readFileSync("./dados/video/venomprivat.mp4")
global.log0 = fs.readFileSync("./dados/imagem/venom.jpg")

global.limitawal = {
    premium: "Infinity",
    free: 100
}
   global.rpg = {
   darahawal: 100,
   besiawal: 5,
   goldawal: 1,
   emeraldawal: 1,
   umpanawal: 1,
   potionawal: 1
}
//=================================================//
let file = require.resolve(__filename)
fs.watchFile(file, () => {
	fs.unwatchFile(file)
	console.log(chalk.redBright(`${__filename} foi atualizado`))
	delete require.cache[file]
	require(file)
})