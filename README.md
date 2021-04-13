import java.util.*;
class Form
{
	String name;
	int password;
	String formName()
	{
		Scanner scan=new Scanner(System.in);
		System.out.println("Enter Your Name");
		name=scan.next();
		return name;
	}
	int formPassword()
	{
		Scanner scan=new Scanner(System.in);
		System.out.println("Enter Your Password");
		password=scan.nextInt();
		System.out.println("-----------------------------------------------------------------------------------------------------------------");
		System.out.println("                                                   Welcome"+ "  "+name                                );
		System.out.println("-----------------------------------------------------------------------------------------------------------------");
		return password;
	}
}


class Category
{
	int category;
	int categoryInput()
	{
		System.out.println("1.FICTION");
		System.out.println("2.ROMANTIC");
		System.out.println("3.COMICS");
		System.out.println("4.NON-FICTION");
		System.out.println("5.SCIENCE & TECHNOLOGY");

		Scanner scan=new Scanner(System.in);
		System.out.println("Enter Your Choice");
		category=scan.nextInt();
		System .out .println("----------------------------------------------------------------------------------------------------------------");
		if(category==1){
		System.out.println("1.THE BRAHMIN");
		System.out.println("2.A TALE OF TWO CITIES");
		System.out.println("3.THE ALCHEMIST");
		System.out.println("4.HARRY POTTER");
		System.out.println("5.ALICE'S ADVENTURES IN WONDERLAND");
		}

		else if(category==2){
		System.out.println("1.TWILIGHT");
		System.out.println("2.HALF WAY TO THE GRAVE");
		System.out.println("3.PERFECT CHEMISTRY");
		System.out.println("4.REASON TO BREATHE");
		System.out.println("5.YOU WERE MY CRUSH");
		}

		else if(category==3){
		System.out.println("1.WOLVERINE");
		System.out.println("2.BATMAN");
		System.out.println("3.STAR WARS");
		System.out.println("4.JUSTICE LEAUGE");
		System.out.println("5.AVENGERS");
		}

		else if(category==4){
		System.out.println("1.A BREIF HISTORY OF TIME");
		System.out.println("2.IN COLD BLOOD");
		System.out.println("3.HIROSHIMA");
		System.out.println("4.THE DIARY OF A YOUNG GIRL");
		System.out.println("5.ENDURANCE");
		}

		else if(category==5){
		System.out.println("1.SAPIENS");
		System.out.println("2.SUPERINTELLIGENCE");
		System.out.println("3.ELON MUSK");
		System.out.println("4.PACKING FOR MARS");
		}


		else {
			System.out.println("Please enter a valid option!!!");
		}
		return category;
	}
}


class Fiction
{
	int fiction;

	int fictionInput()
	{
		Scanner scan =new Scanner(System.in);
		System.out.println("Choose Your Book");
		fiction=scan.nextInt();
		System.out.println("------------------------------------------------------------------------------------------------------------------");

		if(fiction==1){
			System.out.println("THE BRAHMIN");
			System.out.println("By:- Ravi Shankar Etteth");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("It is a time of violence as well as calm. Men of peace are spreading the message of the Buddha even as monks are being tortured in the dungeons of Pataliputra. In Magadha, all talk is about the impending war against Kalinga. While King Ashoka plots the movements of his ships and cavalry, Queen Asandhimitra broods over the growing unrest in the kingdom. There is only one man they can both trust to take them through this period of uncertainty and looming danger: the enigmatically named Brahmin, skilful spymaster and custodian of Magadha’s best-kept secrets.");
		}

		else if(fiction==2){
			System.out.println("A TALE OF TWO CITIES");
			System.out.println("By:-Charles Dickens");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("It was the best of times, it was the worst of times, it was the age of wisdom, it was the age of foolishness, it was the epoch of belief, it was the epoch of incredulity, it was the season of Light, it was the season of Darkness, it was the spring of hope, it was the winter of despair, we had everything before us, we had nothing before us, we were all going direct to Heaven, we were all going direct the other way—in short, the period was so far like the present period, that some of its noisiest authorities insisted on its being received, for good or for evil, in the superlative degree of comparison only.");
		}

		else if(fiction==3){
			System.out.println("THE ALCHEMIST");
			System.out.println("By:-Paulo Coelho");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("The Alchemist follows the journey of an Andalusian shepherd boy named Santiago. Believing a recurring dream to be prophetic, he asks a Romani fortune teller in a nearby town about its meaning. The woman interprets the dream as a prophecy telling the boy that he will discover a treasure at the Egyptian pyramids");
		}

		else if(fiction==4){
			System.out.println("HARRY POTTER");
			System.out.println("By:-J.K. Rowling");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Harry Potter, a boy who learns on his eleventh birthday that he is the orphaned son of two powerful wizards and possesses unique magical powers of his own. He is summoned from his life as an unwanted child to become a student at Hogwarts, an English boarding school for wizards. There, he meets several friends who become his closest allies and help him discover the truth about his parents' mysterious deaths.");
		}

		else if(fiction==5){
			System.out.println("ALICE'S ADVENTURES IN WONDERLAND");
			System.out.println("By:-Lewis Carroll");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Alice’s sister is reading a picture-less book, which bores Alice. Then, she sees a White Rabbit run right past her. The rabbit takes a watch out of his waistcoat and exclaims that he’ll soon be late. After that, he jumps down a rabbit hole. This mysterious event intrigues Alice and she runs after him.");
		}
			
		else{
			System.out.println("please enter a valid option");
		}
		return fiction;
	}
}

class Romantic
{
	int romantic;

	int romanticInput()
	{
		Scanner scan =new Scanner(System.in);
		System.out.println("Choose Your Book");
		romantic=scan.nextInt();
		System.out.println("------------------------------------------------------------------------------------------------------------------");
		if(romantic==1){
			System.out.println("TWILIGHT");
			System.out.println("By:-Stephenie Meye");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Bella Swan and the vampire she falls in love with, Edward Cullen. Bella moves to the small and rainy town of Forks, Washington, to live with her father after her mother remarries. She hates the rain, but at least she fits in better in Forks than she did in her huge high school in Phoenix, Arizona.");
		}

		else if(romantic==2){
			System.out.println("HALF WAY TO THE GRAVE");
			System.out.println("By:-Jeaniene Frost");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("As the story opens, twenty-two year-old Cat is driving in her truck in the middle of the night when she is stopped by the police. Her taillight is out. But she’s not worried about her taillight; what she has in the bed of her truck would be much more difficult to explain. She has the dead body of a vampire who is bleeding out. She had tussled with him earlier and drove a silver stake into his heart, ending his centuries-old life.");
		}

		else if(romantic==3){
			System.out.println("PERFECT CHEMISTRY");
			System.out.println("By:-Simone Elkeles");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Brittany Ellis is the daughter of wealthy parents from the right side of town. She appears to be a girl who seems to have it all. Alex Fuentes is a poor Mexican boy from the wrong side of town who became a member of the local gang to protect his mother and two little brothers. When Alex and Brittany are forced to become partners in their chemistry class, they find themselves on a path that will lead both to discover that looks are not all they appear to be. ");
		}

		else if(romantic==4){
			System.out.println("REASON TO BREATHE");
			System.out.println("By:- Rebecca Donovan");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("The town of Weslyn, Connecticut, is wealthy and quiet. Emma is an excellent student who also plays three varsity sports. She is best friends with Sara, the prettiest and most popular girl in school. Emma lives with her aunt and uncle, after the death of Emma's father (her uncle's brother), and the distance of her alcoholic mother. ");
		}

		else if(romantic==5){
			System.out.println("YOU WERE MY CRUSH");
			System.out.println("By:-Durjoy Datta");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("It’s a story about Benoy Roywho has a big house (in which he lives alone), a big car (but he doesn’t has a buddy to accompany) and moreover a Rich Dad (with whom he doesn’t has good relation) who provides him everything he wants. Despite having everything he has nothing. He was just a Rich Brat in everyone’s eyes. Everyone thought that he has everything but nobody knows that he has nothing to care about in his life. He lost his mother one year ago due to cancer and doesn’t have Father-Son relation with his Dad. ");
		}


		else{
			System.out.println("please enter a valid option");
		}
		return romantic;
	}
}

class Comics
{
	int comics;

	int comicsInput()
	{
		Scanner scan =new Scanner(System.in);
		System.out.println("Choose Your Book");
		comics=scan.nextInt();
		System.out.println("------------------------------------------------------------------------------------------------------------------");
		if(comics==1){
			System.out.println("WOLVERINE");
			System.out.println("By:-Marvel comic");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("This story the first meeting of Wolverine and Captain America on the streets of Lowtown, Madripoor 50 years past is a fantastic example of the dynamic storytelling Jim Lee brought to the X-Men. Lee’s rendition of Logan rivals John Byrne’s in terms of capturing a distinct style and characterization, signaling another redefining moment for the popular hero.");
		}

		else if(comics==2){
			System.out.println("BATMAN");
			System.out.println("By:-DC comic");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Batman has been Gotham's protector for decades, CEO of Wayne Enterprises, Patriarch of the Bat Family and veteran member of the Justice League. Batman is a superhero co-created by artist Bob Kane and writer Bill Finger and published by DC Comics. The character made his first appearance in Detective Comics #27 (May, 1939). Batman is the secret identity of Bruce Wayne. Witnessing the murder of his parents as a child leads him to train himself to physical and intellectual perfection and don a bat-themed costume in order to fight crime. Batman operates in Gotham City, assisted by various supporting characters including his sidekick Robin and his butler Alfred Pennyworth, and fights an assortment of villains influenced by the characters' roots in film and pulp magazines. Unlike most superheroes, he does not possess any superpowers; he makes use (to the best that he can) of intellect, detective skills, science and technology, wealth, physical prowess, and intimidation in his war on crime.");
		}

		else if(comics==3){
			System.out.println("STAR WARS");
			System.out.println("By:-??Dark Horse Comics");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("A story addressing Leia’s post New Hope grief and how’s she processing the loss of her planet. And that’s…pretty much the premise of the entire comic. It explains why Leia seems so stoic as she sets out on a (very much unsanctioned) mission to rescue the remaining Alderaanian refugees before the Empire can wipe them out entirely");
		}

		else if(comics==4){
			System.out.println("JUSTICE LEAUGE");
			System.out.println("By:-??DC comic");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("The Justice League is the DC Universe's most powerful and premier superhero team. A strike force comprised of the world's mightiest heroes. They act as stalwart protectors of sentient life; Earth's first line of defense against terrestrial, extra-terrestrial, inter-dimensional and supernatural threats. There have been many members over the years and several incarnations of the team, but the original group was founded by Aquaman, Batman, Flash, Green Lantern, Martian Manhunter, Superman, and Wonder Woman");
		}

		else if(comics==5){
			System.out.println("AVENGERS");
			System.out.println("By:-MARVEL comic");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Marvel sought to unite its biggest names in a single book. The Avengers, however, was anything but a carbon copy of Justice League. Marvel’s team was characterized by internal conflict, and it owed its existence largely to the machinations of a villain. Loki, the Norse god of mischief, maneuvers his half brother, the thunder god Thor, into a battle against the Hulk. This fracas also attracts the attention of Iron Man and the crime-fighting duo of Ant-Man and the Wasp. Although this quartet at first believes the Hulk to be the villain responsible for an act of railway sabotage, Loki quickly emerges as the real culprit and suffers a decisive defeat. Before the heroes disperse, Ant-Man suggests that they make their association a permanent one, and the Avengers (a name suggested by the Wasp) are born.");
		}

		else{
			System.out.println("Please select a valid option");
		}
		return comics;
	}
}


class Non_Fiction
{
	int nonFiction;

	int nonFictionInput()
	{
		Scanner scan =new Scanner(System.in);
		System.out.println("Choose Your Book");
		nonFiction=scan.nextInt();
		System.out.println("------------------------------------------------------------------------------------------------------------------");
		if(nonFiction==1){
			System.out.println("A BREIF HISTORY OF TIME");
			System.out.println("By:-Stephen Hawking");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("In A Brief History of Time, Hawking writes in non-technical terms about the structure, origin, development and eventual fate of the Universe, which is the object of study of astronomy and modern physics. He talks about basic concepts like space and time, basic building blocks that make up the Universe (such as quarks) and the fundamental forces that govern it (such as gravity). He writes about cosmological phenomena such as the Big Bang and black holes. He discusses two major theories, general relativity and quantum mechanics, that modern scientists use to describe the Universe. Finally, he talks about the search for a unifying theory that describes everything in the Universe in a coherent manner.");
		}

		else if(nonFiction==2){
			System.out.println("IN COLD BLOOD");
			System.out.println("By:-Truman Capote");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("It details the 1959 murders of four members of the Herbert Clutter family, who lived in the small farming community of Holcomb, Kansas.  When Capote learned of the quadruple murders (before the killers were captured) he traveled to Kansas and write about the crime.  He was accompanied by his childhood friend and fellow author Harper Lee, and together they interviewed local residents and investigators assigned to the case and took thousands of pages of notes.");
		}

		else if(nonFiction==3){
			System.out.println("HIROSHIMA");
			System.out.println("By:-John Hersey");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Hiroshima, by John Hersey, deals with the human impact of the atomic bomb used on Hiroshima in 1945. Chapter 1 begins on the morning of the dropping of the atomic bomb (August 6 1945), resulting in the deaths of over one-hundred-thousand people. Throughout the chapter, the reader is introduced to 6 individuals.");
		}

		else if(nonFiction==4){
			System.out.println("THE DIARY OF A YOUNG GIRL");
			System.out.println("By:-Anne Frank");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Anne’s diary begins on her thirteenth birthday, June 12, 1942, and ends shortly after her fifteenth. At the start of her diary, Anne describes fairly typical girlhood experiences, writing about her friendships with other girls, her crushes on boys, and her academic performance at school. Because anti-Semitic laws forced Jews into separate schools, Anne and her older sister, Margot, attended the Jewish Lyceum in Amsterdam. The Franks had moved to the Netherlands in the years leading up to World War II to escape persecution in Germany. After the Germans invaded the Netherlands in 1940, the Franks were forced into hiding.");
		}

		else if(nonFiction==5){
			System.out.println("ENDURANCE");
			System.out.println("By:-Alfred Lansing");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("The veteran of four spaceflights and the American record holder for consecutive days spent in space, Scott Kelly has experienced things very few have. Now, he takes us inside a sphere utterly hostile to human life. He describes navigating the extreme challenge of long-term spaceflight, both life-threatening and mundane: the devastating effects on the body; the isolation from everyone he loves and the comforts of Earth; the catastrophic risks of colliding with space junk; and the still more haunting threat of being unable to help should tragedy strike at home--an agonizing situation Kelly faced when, on a previous mission, his twin brother's wife, American Congresswoman Gabrielle Giffords, was shot while he still had two months in space.");
		}

		else{
			System.out.println("Please select a valid option");
		}
		return nonFiction;
	}
}


class SciTech
{
	int sciTech;

	int sciTechInput()
	{
		Scanner scan =new Scanner(System.in);
		System.out.println("Choose Your Book");
		sciTech=scan.nextInt();
		System.out.println("------------------------------------------------------------------------------------------------------------------");
		if(sciTech==1){
			System.out.println("SAPIENS");
			System.out.println("By:- Yuval Noah Harari");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Human history has been shaped by three major revolutions: the Cognitive Revolution (70,000 years ago), the Agricultural Revolution (10,000 years ago), and the Scientific Revolution (500 years ago). These revolutions have empowered humans to do something no other form of life has done, which is to create and connect around ideas that do not physically exist (think religion, capitalism, and politics). These shared “myths” have enabled humans to take over the globe and have put humankind on the verge of overcoming the forces of natural selection.");
		}

		else if(sciTech==2){
			System.out.println("SUPERINTELLIGENCE");
			System.out.println("By:-Nick Bostrom");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("It is unknown whether human-level artificial intelligence will arrive in a matter of years, later this century, or not until future centuries. Regardless of the initial timescale, once human-level machine intelligence is developed, a 'superintelligent' system that 'greatly exceeds the cognitive performance of humans in virtually all domains of interest' would, most likely, follow surprisingly quickly. Such a superintelligence would be very difficult to control or restrain. While the ultimate goals of superintelligences can vary greatly, a functional superintelligence will spontaneously generate, as natural subgoals, 'instrumental goals' such as self-preservation and goal ");
		}

		else if(sciTech==3){
			System.out.println("ELON MUSK");
			System.out.println("By:-Ashlee Vance");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Who’s heard of the eccentric CEO of Tesla Motors, Elon Musk? He is one of the most unpredictable and ambitious entrepreneurs in Silicon Valley, and the press always labels him as the next Steve Jobs. South African boy Musk has always been passionate about technology, space, and renewable energy and moved to the United States as a teenager. His goal was to unite his passions and to start businesses and, without worrying about money, he became one of the 100 richest men in the world. Explore the history of this great visionary and discover how he has dedicated his energies to reinvent the future beyond science fiction films in this unique 12' microbook.");
		}

		else if(sciTech==4){
			System.out.println("PACKING FOR MARS");
			System.out.println("By:-Mary Roach");
			System.out.println("-----------------------------------------------------------------------------------------------------------------");
			System.out.println("Although Packing for Mars covers broad technical questions about space travel, Roach focuses primarily on the practical realities of humans existing in space. She tackles issues such as sex, bodily functions, and loneliness, believing that most of us fail to appreciate how taxing space travel is. Roach’s thesis is that it is much harder to keep humans alive and healthy in space than we imagin");
		}


		else{
			System.out.println("Please select a valid option");
		}
		return sciTech;

	}
}


class Buy
{
	int buy;
	int buy()
	{
		Scanner scan =new Scanner (System.in);
		System.out.println("------------------------------------------------------------------------------------------------------------------");
		System.out.println("If You want to download the copy of any book ,You have to buy our prime membership @ Rs 999");
		System.out.println("If You want to buy the subscription choose 1");
		System.out.println("For exit choose 0");
		buy=scan.nextInt();
		if(buy==1){
			System.out.println("1.Debit card");
			System.out.println("2.Paytm");
			System.out.println("3.BHIM UPI");
		}

		else{
			System.out.println("you can checkout other time!!!!!");
		}
		return buy;
	}
}

class Payment
{
	int mode;
	void mode()
	{
		Scanner scan=new Scanner(System.in);
		System.out.println("--------------------------------------------------------------------------------------------------------------------");
		System.out.println("Select any Payment mode to proceed:-");
		mode=scan.nextInt();

		if(mode==1){
			int card_no;
			int cvv;
			int exp_year;
			System.out.println("Enter your card number:-");
			card_no=scan.nextInt();
			System.out.println("Enter your CVV:-");
			cvv=scan.nextInt();
			System.out.println("Expiry year of Card:-");
			exp_year=scan.nextInt();
			System.out.println("Payment Successful!!!!!");
			System.out.println("Enjoy the prime membership!!!!");
		}

		else if(mode==2){
			int paytm_no;
			System.out.println("Enter your Paytm number");
			paytm_no=scan.nextInt();
			System.out.println("Payment Successful!!!");
			System.out.println("Enjoy the prime membership!!!!");
		}

		else if(mode==3){
			int upi_id;
			System.out.println("Enter your BHIM upi id");
			upi_id=scan.nextInt();
			System.out.println("Payment Successful!!!!");
			System.out.println("Enjoy the prime membership!!!!");
		}


		else{
			System.out.println("plzzz enter valid option");
		}
		System.out.println("-------------------------------------------------------------------------------------------------------------------");
	}

}


	
				
class Gyaan
{
	public static void main(String[] args) 
	{
		System.out.println("===================================================================================================================");
		System.out.println("                                           || WELCOME TO GYAAN hUB ||                            ");
		System.out.println("===================================================================================================================");

		Form f=new Form();
		f.formName();
		f.formPassword();

		Category c=new Category();
		int category=c.categoryInput();
		if(category==1){
			Fiction fi=new Fiction();
			fi.fictionInput();
		}
		else if(category==2){
				Romantic ro=new Romantic();
				ro.romanticInput();
		}
		else if(category==3){
				Comics co=new Comics();
				co.comicsInput();
		}

		else if(category==4){
				Non_Fiction nf=new Non_Fiction();
				nf.nonFictionInput();
		}

		else{
				SciTech st=new SciTech();
				st.sciTechInput();
		}

		Buy b=new Buy();
		int buy=b.buy();
     if(buy==1)
     {
		 Payment p=new Payment();
		 p.mode();
     }
	 else
		{
		 System.out.println("Thanks for visiting");
		}
	 
	}
}
