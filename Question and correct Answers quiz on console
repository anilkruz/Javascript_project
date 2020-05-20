# Javascript_project
/--code challenge 7

(function(){
    function Question(question,answers,correct){
    this.question =question;
    this.answers =answers;
    this.correct =correct;
}
Question.prototype.displayquestion = function(){
        console.log(this.question);
    for(var i =0;i<this.answers.length;i++){
        console.log(i + ':'+this.answers[i]);
    }
    
}
Question.prototype.correctAns = function(ans,callback){
//    var sc;
            if (ans === this.correct) {
            console.log('Correct answer!');
                console.log("Your score:-"+callback(true));

        } else {
            console.log('Wrong answer. Try again :)')
            console.log("Your score:-"+callback(false));
        }
}
var q1 = new Question("Is JavaScript the coolest programming language in the world?",['YES','NO'],0);
var q2 = new Question("What is the name of this course\'s teacher?",['jones','micheal','Anil'],2);
var q3 = new Question('What does best describe coding?',['Boring', 'Hard', 'Fun', 'Tediuos'],2);
var question = [q1,q2,q3];
    function score(){
        
    }
    function score(){
        var sc =0;
        return function(correct){
            if (correct){
                sc++;
            }
            return sc;
        }
    }
    var keepscore = score();
nestquestion();
function nestquestion(){
    
var q = Math.floor(Math.random()*question.length);
question[q].displayquestion();
var a =  prompt("Please enter the answer");
      console.log(a)

    if(a !== 'exit'){
        
question[q].correctAns(parseInt(a),keepscore);        
    nestquestion();
    }else
        return -1;
    
}


})();
 
