- 👋 Hi, I’m @TraineeCodee
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
TraineeCodee/TraineeCodee is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#include<stdio.h>
#include<stdlib.h>
#include<time.h>

int main() {

	setbuf(stdout,NULL);

	char player1 [20];
	char player2[20];
	int n,j;
	printf("who is player 1? ");
	scanf("%s",player1);
	printf("welcome %s\n", player1);

	printf("who is player 2? ");
		scanf("%s",player2);
		printf("welcome %s\n", player2);

		printf("Player 1 roll  the dice\n");
		int c;
		printf("Press '1' to roll the dice\n");
		scanf("%d",&c);



		srand(time(NULL));
				n=rand()%4+2;
				printf("Your number is %d\n",n);
				printf("Player 2 roll the dice\n");
				int d;
				printf("Press '1' to roll the dice\n");
				scanf("%d",&d);





				srand(time(NULL));
				j=rand()%5+1;
				printf("Your number is %d\n",j);
if(n<j){
	printf("%s Wins the match",player2);
}else if(j<n){
	printf("%s Wins the match",player1);
}else{
	printf("Match is draw");
}


return 0;

}
