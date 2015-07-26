/**
 * 
 */
package ua.org.gostroy.mule_example_echo.service;

import javax.jws.WebParam;
import javax.jws.WebResult;
import javax.jws.WebService;

/**
 * @author Sergey
 *
 */
@WebService
public class Echo {

	@WebResult(name="text")
    public String echo(@WebParam(name="text") String string){
        return string;
    }
}
