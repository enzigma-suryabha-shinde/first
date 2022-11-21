public class RandomContactFactory {
    
    public static List<Contact> generateRandomContacts(Integer num, String lastName)
    {
        list<Contact> conList = new List<COntact>();
        for(Integer i=0; i<num; i++)
        {
            Contact c = new Contact(FirstName = 'abcd' +i, LastName= 'efgh');
            
            conList.add(c);
        }
        return conList;
    }



}
