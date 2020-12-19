#NOTA vedeti ca mai trebuie sa adaugati alte liste, de exemplu aveti "Some aqua Dive Rings" faceti liste separate daca e cate un obiect de asta ciudat
#de exemplu cum am facut eu pentru microfon, pc etc...
#daca mai gasiti niste culori, le puteti adauga si voi, nu e nicio problema
# V-jos, ^- sus
#S-AR PUTEA SA NU INTRU LA 9:30 FIINDCA DORM, DACA E ASA, IL PUNETI PE RAZVAN NITU SA MA SUNE sau Teodora daca e prezenta pe voice, dar bag mana in foc ca nu se trezeste. :))
#daca nu ma insel puteti apela functia celor de la echipa1 (cred)
#faceti si voi niste teste sa vedeti daca merge, pupic
import re
class colors:
    green=0
    red=0
    violet=0
    blue=0
    yellow=0
    orange=0
    brown = 0
    black = 0
    magenta = 0
    pink = 0
    dark_blue = 0
    golden = 0
    purple = 0
    cyan= 0
    white = 0
    silver = 0
    gray = 0
color=colors()
#va da eroare ca nu exista clasa "gift" V
pcolor=gift.adjective
a = 'Huawei Horizon phone scarf'

phones = ['huawei', 'iphone', 'samsung', 'xiaomi', 'nokia', 'lg', 'oneplus']
tablet= [ 'tablet']
pc=['computer']
laptop=['laptop']
accessories_pc=['keyboard']
mic=['microphone']
food = ['cheese', 'candy', 'fruit', 'chocolate', 'wafers']
care=['oral-b']
consoles = ['nintendo', 'playstation', 'xbox','console']
components = ['amd', 'intel', 'nvidia']
pants=['pants']
backpack=['backpack','handbag']
scarf=['scarf']
wig=['wig']
shorts=['shorts']
bed=['blanket']
pillow=['pillow']
shoes=['sandals','shoes','stiletto','slippers']
dress=['dress']
hoodie=['shirt','hoodie','t-shirt']
paper = ['poster', 'book', 'giftcard']

for i in a:
    declassified = 0
    toy = re.split(" ", i.obj)
    for j in toy:
        if j.lower() in components:
            declassified = 1
            a=(6*24*12)/100000
            if pcolor!= None:
                if pcolor=='green':
                    color.green=color.green + a
                elif pcolor == 'red':
                    color.red=color.red + a
                elif pcolor == 'violet':
                    color.violet=color.violet + a
                elif pcolor == 'blue':
                    color.blue=color.blue + a
                elif pcolor == 'yellow':
                    color.yellow=color.yellow + a
                elif pcolor == 'orange':
                    color.orange=color.orange + a
                elif pcolor=="brown":
                    color.brown=color.brown + a
                elif pcolor=='black':
                    color.black=color.black + a
                elif pcolor==' magenta':
                    color.magenta=color.magenta +a
                elif pcolor=='pink':
                    color.pink=color.pink + a
                elif pcolor=="dark_blue":
                    color.dark_blue=color.dark_blue + a
                elif pcolor=='golden':
                    color.golden=color.golden + a
                elif pcolor=='purple':
                    color.purple=color.purple + a
                elif pcolor=='cyan':
                    color.cyan=color.cyan + a
                elif pcolor=='white':
                    color.white=color.white + a
                elif pcolor=='silver':
                    color.silver=color.silver + a
                elif pcolor=='gray':
                    color.gray=color.gray + a
            elif
                pass
            #elif  Aici faceti si voi o functie care sa aleaga random o culoare, atentie, daca culoarea preferata este precizata, folositi culoarea preferata daca nu, cu functia random
            #exemplu gasiti pe #echipa1

            #procesoarele nu se coloreaza lol, tot ce e mai sus trebuie doar sa dati copy paste pentru fiecare lista V, dupa ce ati facut functia ce e la linia 95, stergeti toate "elifurile" pt culori

            break
            #la console nush, puneti direct alb si negru, nu mai trebuie sa folositi toate if-urile de la "components" faceti cu o functie random doar pentru
            #culorile alb si negru
        elif j.lower() in consoles:
            declassified = 1
            a=(6*41*30)/100000
            break
        elif j.lower() in phones:
            declassified = 1
            a=(6*16*7)/100000
            break
        elif j.lower() in tablet:
            declassified = 1
            a=(6*22*30)/100000
            break
        elif j.lower() in pc:
            declassified = 1
            a=(6*42*44)/100000
            break
        elif j.lower() in laptop:
            declassified = 1
            a=(6*40*24)/100000
            break
        elif j.lower() in accessories_pc:
            declassified = 1
            a=(6*47*20)/100000
            break
        elif j.lower() in mic:
            declassified = 1
            a=(6*17*5)/100000
            break
        elif j.lower() in care:
            declassified = 1
            a=(6*18*2)/100000
            break
        elif j.lower() in pants:
            declassified = 1
            a=(6*100*40)/100000
            break
        elif j.lower() in backpack:
            declassified = 1
            a=(6*50*35)/100000
            break
        elif j.lower() in scarf:
            declassified = 1
            a=(6*130*20)/100000
            break
        elif j.lower() in wig:
            declassified = 1
            a=(6*34*18)/100000
            break
        elif j.lower() in shorts:
            declassified = 1
            a=(6*40*40)/100000
            break
        elif j.lower() in bed:
            declassified = 1
            a=(6*200*200)/100000
            break
        elif j.lower() in pillow:
            declassified = 1
            a=(6*65*35)/100000
            break
        elif j.lower() in shoes:
            declassified = 1
            a=(6*25*10)/100000
            break
        elif j.lower() in dress:
            declassified = 1
            a=(6*100*42)/100000
            break
        elif j.lower() in hoodie:
            declassified = 1
            a=(6*55*42)/100000
            break
        elif j.lower() in food:
            declassified = 1
            break
        elif j.lower() in paper:
            declassified = 1
            a=(6*30*20)/100000
            break
        elif j.lower() == 'bike' or j.lower() == 'bicycle':
            declassified = 1
            a=(6*80*50)/100000
            break
        elif j.lower() == "ball":
            declassified = 1
            a=(6*23*23)/100000
            #informatie preluata de pe net, so stfu
            break
        elif j.lower() == 'doll':
            declassified = 1
            a=(6*45*25)/100000
            break
        elif j.lower() == 'skateboard' or j.lower() == 'skate':
            declassified = 1
            a=(6*90*25)/100000
            break
    if declassified == 0:
        pass
  #daca nu gasiti nici de cum cuvantul cheie, dati doar o valoare random ex: a=(6*20*12)/100000

