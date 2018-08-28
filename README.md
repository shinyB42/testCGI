# testCGI
Fuckin test de marde que j'essaye de solutionner
Gatez-vous


static void Main(string[] args)
        {
            List<int> array = new List<int>() {8,3,9,4,10,12,5,2,8,1};

            printArray(array);
            Console.ReadLine();
        }

        public static void printArray(List<int> test){

            
            for (int i = 0; i < test.Count-1; i++)
            {

                if (i!=0 &&(test[i]<test[i+1] || i + 2 >= test.Count ))
                {
                    Console.WriteLine(test[i + 1]);
                }
                else if (i==0 && test[i] < test[i + 1])
                {
                    Console.WriteLine(test[i]);
                }



                

                //compteur++;
                //for (int j = compteur; j < array.Count(); j++) // pourquoi avoir une comparaison avec tout les autres numeros quand on veut seulement comparer avec le prochain numero
                //{
                //    /*if (array[i] > array[j])
                //    {
                //        Console.WriteLine(array[i]);
                //        //Console.WriteLine(Array.IndexOf(array, array[i]));
                //        break;
                //    }*/
                //    Console.WriteLine(Array.IndexOf(array, array[j]));
                //    //if (Array.IndexOf(array, array[i]) == Array.IndexOf(array, array[j])+1)
                    
                //}
            }
        }
